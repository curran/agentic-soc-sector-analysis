# Agentic SOC Sector Analysis

An open dataset for exploring the emerging **AI-powered Security Operations Center (AI-SOC)** market: how AI-native security startups compare with established cybersecurity vendors, what their products claim to do, and how much evidence supports their reported outcomes.

The project tracks companies, products, and published benchmarks as **three linked CSV datasets**. It is intended for exploratory analysis, market research, and data visualization—not as a definitive vendor ranking or independent product evaluation.

**Research snapshot:** November 19, 2026. Information and product availability may change after that date.

## Research questions

- How do AI-native startups and established security vendors differ in positioning, architecture, and go-to-market strategy?
- Which products document capabilities such as alert triage, autonomous investigation, threat hunting, detection engineering, and incident response?
- Where do specialist tools compete with integrated security platforms?
- What quantitative performance claims are publicly available, and how strong is their supporting evidence?
- Where are the gaps in comparable performance, pricing, deployment, and adoption data?

## Datasets

| File | Rows | Columns | Grain |
| --- | ---: | ---: | --- |
| [`companies.csv`](companies.csv) | 15 | 46 | One company |
| [`products.csv`](products.csv) | 33 | 47 | One named product, agent, platform, or service |
| [`benchmarks.csv`](benchmarks.csv) | 92 | 37 | One reported metric **or** explicitly recorded research-coverage gap |

The benchmark file contains **75 quantitative metric records** (`record_type=metric`) and **17 coverage-gap records** (`record_type=coverage_gap`). Coverage gaps do **not** represent zero performance.

### `companies.csv`

Profiles the organizations participating in this market. Fields include `company_id`, `company_name`, `vendor_type`, `ownership_status`, company age and location, market positioning, target customers, funding, revenue/ARR where disclosed, customer traction, competitive risks, and source URLs.

Company-wide financial metrics are **not** necessarily attributable to the AI-SOC product line. Funding and revenue are different measures and should not be placed on one common scale without an explicit analytical purpose. Missing values should not be read as zero.

### `products.csv`

Catalogs primary AI-SOC offerings and adjacent components, including their parent-product relationships. Key fields include `product_id`, `company_id`, `parent_product_id`, `product_role`, `is_primary_ai_soc_offering`, `market_status`, deployment and data architecture, and capabilities such as `alert_triage`, `autonomous_investigation`, `threat_hunting`, `detection_engineering`, and `response_orchestration`.

Capability fields record the presence of **documentation or claims**, not independently verified effectiveness. A blank capability is **unknown**, not proof that a feature is unavailable. Product status also matters: previews, announced offerings, and generally available features should not be conflated.

### `benchmarks.csv`

Captures reported outcomes and the context needed to interpret them. Key fields include `benchmark_id`, `record_type`, `company_id`, `product_id`, `metric_category`, `metric_name`, `metric_value`, range and qualifier fields, `unit`, baseline fields, `measurement_context`, `sample_size`, `methodology`, `source_type`, `study_independence`, `comparability_notes`, and `source_url`.

**Do not rank vendors by raw benchmark percentages or times.** Published measurements may have different workloads, denominators, baselines, populations, observation periods, and definitions. A case study's automation rate is not equivalent to recall against independently labeled attacks; agreement with an analyst is not necessarily attack-detection accuracy.

## Data relationships

The three files use stable IDs:

~~~text
companies.csv                      products.csv                      benchmarks.csv
company_id (PK)  ───────────────<  company_id (FK)  ──────────────<  product_id (FK)
                                   product_id (PK)                    company_id (FK)
                                   parent_product_id (optional)       benchmark_id (PK)
~~~

- Join `companies.company_id = products.company_id`.
- Join `products.product_id = benchmarks.product_id`.
- `benchmarks.company_id` also provides a direct company reference; validate it against the product's company when combining files.
- `products.parent_product_id` links related components to another product record when populated.
- Relationships are **one-to-many**: do not count a company once per product or benchmark record. For company-level summaries, aggregate at the appropriate grain first.

At the November 19 snapshot, the company and product identifiers are unique and all product/benchmark foreign keys resolve to their corresponding records.

## Quick start

The repository is data-first: no application build, API keys, or third-party Python packages are required to inspect it.

Clone the repository and run the following with Python 3:

~~~bash
git clone https://github.com/curran/agentic-soc-sector-analysis.git
cd agentic-soc-sector-analysis
python3 - <<'PY'
import csv
from pathlib import Path

def load(filename):
    with Path(filename).open(newline="", encoding="utf-8-sig") as file:
        return list(csv.DictReader(file))

companies = load("companies.csv")
products = load("products.csv")
benchmarks = load("benchmarks.csv")

company_ids = {row["company_id"] for row in companies}
product_ids = {row["product_id"] for row in products}

assert len(company_ids) == len(companies)
assert len(product_ids) == len(products)
assert all(row["company_id"] in company_ids for row in products)
assert all(row["company_id"] in company_ids for row in benchmarks)
assert all(row["product_id"] in product_ids for row in benchmarks)

metrics = [row for row in benchmarks if row["record_type"] == "metric"]
gaps = [row for row in benchmarks if row["record_type"] == "coverage_gap"]

print(f"{len(companies)} companies, {len(products)} products")
print(f"{len(metrics)} metric observations, {len(gaps)} coverage gaps")
PY
~~~

Use a CSV-aware parser rather than splitting lines or commas manually; quoted CSV fields may contain commas or other special characters.

## Suggested analyses

1. **Market map:** Compare `vendor_type`, `ai_soc_positioning`, and `product_role` to distinguish specialist overlays from broader security platforms.
2. **Capability matrix:** Show primary offerings against documented capability fields; keep missing cells visibly distinct from confirmed absences.
3. **Product landscape:** Explore product families, parent-child relationships, availability, and architecture choices.
4. **Benchmark evidence explorer:** Group metrics by `metric_category` and definition, displaying their context, qualification, provenance, and original source alongside values.
5. **Research coverage:** Show which vendors and products have published measurements and which have explicit evidence gaps.

A quantitative cross-vendor comparison should be attempted **only** where metric definitions and evaluation contexts are genuinely compatible.

## Sources and interpretation

The underlying research was assembled from publicly accessible materials available at the snapshot date. Each CSV includes provenance and verification fields; `PROMPT.md` preserves the research conversation that motivated the dataset.

- Many performance claims originate from vendors, vendor-hosted case studies, commissioned studies, or internal evaluations. Their inclusion is not independent validation.
- `source_type`, `study_independence`, `evidence_quality`, and source URLs should be considered before interpreting an observation.
- Empty fields generally mean **not found, not disclosed, or not verified**; they should not be automatically converted to zero or to “no.”
- Preserve metric qualifiers such as ranges, greater-than bounds, and modeled estimates. Do not silently replace them with exact measurements.
- Treat `last_verified_date` as a research-check date, **not** necessarily the publication date or measurement period.

For consequential procurement or investment decisions, independently verify primary documents, current availability, pricing, and performance under representative workloads.

## Contributing

Corrections, updated source links, and additional measurements are welcome through pull requests. Please preserve existing identifiers and CSV column conventions; supply the original source URL and date; label vendor-reported versus independently assessed claims; and document the evaluation population, sample size, baseline, and metric definition wherever available. Prefer adding a new dated benchmark record over overwriting a historical measurement.

## License

[MIT](LICENSE). Dataset descriptions and source summaries do not supersede the licenses or rights of linked third-party materials.
