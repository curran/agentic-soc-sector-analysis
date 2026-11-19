This is a record of the original ChatGPT conversation from 11/19/26 that generated the data.

>compare AI-SOC startups with established security vendors on product capabilities, differentiation, and competitive positioning

AI-SOC competitive landscape: Startups vs. established security vendors
Market assessment · November 19, 2026 · Product capabilities, differentiation, and competitive positioning
Executive summary
The AI Security Operations Center (AI-SOC) market is shifting from AI-assisted security analysis toward autonomous investigation, threat detection, and incident response.

Startups initially differentiated themselves by automating work that traditional SIEM, XDR, and SOAR platforms left to human analysts. Established cybersecurity vendors are now integrating similar agentic capabilities directly into their platforms.

The central competitive question is no longer who has an AI SOC analyst. It is who can deliver reliable, measurable autonomous security operations with the lowest deployment friction and total cost.

There are three distinct competitive strategies:

1. AI-native specialists — automate the analyst

Companies such as Dropzone AI, Prophet Security, and Intezer operate across existing security tools, emphasizing autonomous triage, evidence gathering, and investigations.




2. AI-native platforms — rebuild security operations

7AI, Exaforce, and Torq aim to automate broader parts of the SOC lifecycle, sometimes competing with traditional SIEM, SOAR, or managed detection and response (MDR) infrastructure.




3. Established platforms — embed AI into the existing stack

Microsoft, CrowdStrike, Palo Alto Networks, Google Cloud, Cisco, and SentinelOne combine agentic workflows with their existing security telemetry, customer relationships, and response controls.



The distinction is rapidly narrowing. Microsoft already supports autonomous alert triage in Defender; CrowdStrike combines agentic investigation with configurable response automation; and SentinelOne announced its integrated Singularity ASOC offering in October 2026. 

Microsoft Learn+2

Overall assessment: Startups retain opportunities in heterogeneous security environments, specialized forensic depth, and faster product iteration. Incumbents have structural advantages in proprietary telemetry, distribution, procurement, and platform integration. The strongest long-term competitors will combine both sets of advantages.
1. AI-SOC startup comparison
The startups are not interchangeable. Some sell an AI analyst to complement an existing SOC; others aim to own the security operations platform.
Company	Core capabilities	Primary differentiation	Competitive positioning
Dropzone AI	Autonomous 24/7 alert triage and investigation	Investigation-focused overlay, designed for deployment over existing tools	Strong fit for lean and midmarket SOCs seeking rapid automation without replacing SIEM/XDR  Dropzone AI
Prophet Security	Multi-step investigations, response, hunting, detection engineering	Evidence-backed investigations and closed-loop detection improvement	Enterprise AI analyst and increasingly comprehensive SOC automation competitor  Prophet Security+1
7AI	Detection, investigation, response, hunting, federated SIEM	Multi-agent operations across tools; federated access to security data; managed-service option	Ambitious AI-native control layer competing for SOC workflow ownership  7AI+1
Exaforce	Detection through response, real-time knowledge graph, AI agents, MDR	Unified security data platform plus autonomous agents and 24/7 managed services	Direct challenger to legacy SIEM/SOC architectures and MDR providers  Exaforce
Torq	Agentic triage, investigation, case management, response orchestration	Combines adaptive AI agents with deterministic workflows and extensive customization	Strong contender for enterprise SOC orchestration and SOAR replacement  Torq
Intezer	Autonomous triage, forensic analysis, sandboxing, reverse engineering	Deep forensic tooling integrated with AI investigation	Specialist differentiation where evidence quality and malware analysis matter  Intezer
Qevlar AI	Autonomous cross-tool investigations, incident reports, remediation guidance	Playbook-independent investigation and organization-level security insights	Attractive to enterprise SOCs and MSSPs operating mixed environments  Autonomous SOC Platform for Hands-Off Defense+1
Simbian	AI SOC agent, threat hunting, AI pentesting	Unifies defensive and offensive security agents in a shared operating model	Differentiates through continuous security validation and self-improving SecOps  Simbian AI

The most important startup competitive clusters










Triage-first automation: Dropzone AI, Qevlar AI

A relatively straightforward buying proposition: automate the costly queue of security alerts without forcing customers to rebuild their security stack. Their exposure is increasing competition from native AI triage inside incumbent products.













Depth and analytical quality: Prophet Security, Intezer

Compete on multi-stage investigation, reproducible evidence, threat analysis, and specialist expertise. These can be more defensible than fast alert summarization.













SOC platform transformation: Exaforce, 7AI

Pursue a larger share of the security budget by controlling the investigation, data access, automation, and managed operations experience. Higher potential contract value comes with more complex enterprise competition.













Workflow infrastructure: Torq

Differentiates through integration breadth, adaptable workflows, and controlled execution. Its competitive advantage is not only reasoning quality but the ability to translate security decisions into operational actions.



An important market development: on August 19, 2026, Cribl acquired Radiant Security's AI-SOC technology assets. Radiant should therefore not be treated as an unchanged independent startup when assessing the competitive landscape. The acquisition illustrates how established security-data infrastructure vendors can enter autonomous operations through acquisitions. 

Cribl

2. Established security vendor comparison
Vendor / product	Capabilities and advantages	Competitive limitation or trade-off
Microsoft — Security Copilot, Defender XDR, Sentinel	Autonomous triage agents, incident analysis, threat intelligence, investigation, and remediation guidance. Tight integration across Microsoft security and identity products.  Microsoft Learn	Particularly compelling for Microsoft-heavy environments; buyers with heterogeneous stacks must validate third-party investigation depth and supported workloads.
CrowdStrike — Falcon, Charlotte AI, Next-Gen SIEM	Strong endpoint and identity context, automated detection triage, agentic investigations, response workflows, and customizable agents with governed execution.  CrowdStrike.com+1	Greatest native advantage for Falcon customers. Depth and economics across non-Falcon sources require evaluation.
Palo Alto Networks — Cortex XSIAM, AgentiX	Integrated SIEM/XDR/SOAR architecture, agentic workflow building, response automation, and enterprise policy controls.  Palo Alto Networks+1	More transformational platform adoption; may be excessive for customers seeking a lightweight AI analyst layer.
Google Cloud — Google SecOps, Gemini agents	SIEM/SOAR platform with generally available automated alert investigation, threat intelligence, hunting, and emerging detection engineering capabilities.  Google Cloud Blog	Some newer workflows remain in preview, including Agentic Chat as of October 30, 2026.  Community
Cisco / Splunk — Enterprise Security AI agents	Deep log analytics, detection engineering, AI-assisted triage, investigation, guided response, and customizable automation.  Platform (last updated 2026-11-03T23:49:26.517Z)	Existing data architecture and operating complexity may remain; availability and licensing differ by agent and product edition.
SentinelOne — Purple AI, Singularity ASOC	Endpoint-native AI investigation, SIEM, data pipelines, case management, hyperautomation, and governed autonomous response.  SentinelOne	ASOC was unveiled in October 2026; buyers should distinguish announced suite capabilities from generally available, licensed functionality.

Why incumbents have a structural advantage
Their most consequential advantage is not necessarily the sophistication of their LLMs. It is their control over the underlying security environment.
- First-party telemetry: Native EDR, cloud, and identity data can reduce evidence gaps.
- Response authority: Existing integrations may permit containment and remediation without a second vendor's authorization layer.
- Distribution: Customers already use their consoles, procurement arrangements, and support channels.
- Governance: Existing enterprise authorization, auditing, and incident-response workflows can support adoption.
- Bundling: AI can be included in platform agreements, weakening the economics of a separate AI analyst product.
However, incumbents also have weaknesses: product complexity, integration bias toward their own ecosystems, legacy workflow design, and potentially expensive changes to existing licensing or data architecture.

AI-native startups can exploit those weaknesses by remaining neutral across competing tools and reducing the effort required to produce an actionable investigation.
3. Head-to-head product capability assessment
The following compares structural strengths rather than assigning numerical scores. Capabilities depend on product edition, deployed integrations, and whether features are generally available.
Capability	AI-native startups	Established vendors	Assessment
Autonomous alert triage	Core product focus	Increasingly native	Converging
Cross-vendor investigation	Often a primary differentiator	Improving, but can favor native ecosystems	Startup opportunity
Endpoint detection and telemetry	Primarily through integrations	Strong first-party capabilities	Incumbent advantage
Deep forensic analysis	Specialist strengths, especially Intezer	Strong in selected platforms	Use-case dependent
Detection engineering and threat hunting	Expanding beyond triage	Broadening rapidly	Competitive convergence
Autonomous containment and response	Growing; varies considerably by vendor	Strong native action and governance infrastructure	Incumbent advantage
SIEM and telemetry infrastructure	Strong in select platform startups	Established scale and deployment base	Incumbent advantage
Workflow customization	Strong for Torq and agent platforms	Strong for mature SOAR ecosystems	Mixed
Vendor-neutral deployment	Central startup selling point	More constrained by platform economics	Startup advantage
Enterprise distribution	Growing	Large installed bases	Incumbent advantage

These are analytical judgments about architectural positioning, not results from independent side-by-side product testing.
4. Competitive positioning map
Broad SOC lifecycle ownership
AI-NATIVE PLATFORM CHALLENGERS

7AI · Exaforce · Torq · Simbian

Cross-stack agents, automation infrastructure, new SOC operating models


INTEGRATED PLATFORM INCUMBENTS

Palo Alto · CrowdStrike · Microsoft · Google · Cisco · SentinelOne

First-party telemetry, integrated detection and response, enterprise distribution


SPECIALIST AUTOMATION OVERLAYS

Dropzone · Qevlar · Prophet · Intezer

Autonomous investigations, forensic depth, targeted workflow improvements


NATIVE AI CAPABILITY EXTENSIONS

Defender agents · Charlotte AI · Splunk agents

Targeted automation embedded within installed security products



Vendor-neutral / cross-stack orientation
Platform-native orientation

Conceptual market map. Some firms span multiple quadrants; placements reflect their primary competitive emphasis rather than exclusive capabilities.
5. Where sustainable differentiation will emerge
A. Investigation accuracy and evidence quality
Fast summaries and plausible explanations are insufficient.

Enterprise customers ultimately need to establish whether agents can discover threats, distinguish true positives from benign behavior, and explain their decisions.

An agent that closes 95% of alerts but silently dismisses critical incidents can be worse than a slower, more conservative system.

For this reason, reliable evidence gathering, uncertainty calibration, and forensic depth may become stronger competitive advantages than headline automation rates.

Research such as SIR-Bench: Evaluating Investigation Depth in Security Incident Response Agents provides a useful direction for benchmarking: distinguish real investigative discovery from merely restating the alert.
B. The security context and data layer
A major strategic divide is emerging around where security context should live.

Exaforce is building a unified data platform and real-time knowledge graph, while 7AI's federated SIEM approach emphasizes operating over data across existing systems. 

Exaforce+1

These represent different competitive bets:
- Centralized context: Normalize and correlate security data ahead of time to support more complete investigations, at the cost of additional data infrastructure.
- Federated context: Investigate across existing systems to minimize data movement and deployment disruption, while accepting dependence on source-system access and performance.
The company that can construct the most useful, trustworthy incident context at the lowest cost may have a durable advantage even as AI models improve.
C. Autonomous response with enterprise governance
Response is where the market moves beyond productivity software.

Customers need agents that can take action, but they also require permissions, approval thresholds, safe execution, audit trails, and rollback where possible.

This favors incumbents with established response infrastructure, but gives startups an opportunity to offer a neutral policy and orchestration layer across different security vendors.
D. Business model and distribution
The pricing battle is likely to be consequential.

Startups must demonstrate that their incremental subscription cost is justified by reduced analyst workload, faster containment, or measurable security improvements.

Incumbents can package AI automation within larger security contracts, potentially offering lower incremental costs to existing customers.

AI-native MDR models offer another route: instead of selling automation as a tool, vendors sell operational security outcomes through a combination of agents and human experts.
6. Competitive outlook
Strong
Cross-platform autonomous investigation

Attractive where organizations operate several SIEM, endpoint, cloud, and identity products. An independent agent that investigates consistently across all of them has a clear reason to exist.



Strong
Deep forensic and evidence-driven specialization

Technically demanding capabilities can preserve differentiation even when basic triage becomes commonplace.



Mixed
Full-stack AI-native SOC replacement

Higher potential contract value and strategic control, but direct competition with established SIEM/XDR vendors and significant migration hurdles.



At risk
Standalone alert summarization and basic triage

Increasingly exposed to commoditization through native agents, improved foundation models, and bundling.



My directional expectation for the next 12–24 months is continued consolidation and convergence. The independent vendors most likely to remain strategically relevant will either own a major portion of SOC operations or deliver specialized capabilities that platform providers struggle to replicate.

This is a forecast, not a verified prediction of vendor performance.
7. Which companies are best positioned for different customers?
Customer profile	Most relevant vendors to evaluate	Why
Microsoft-centric enterprise	Microsoft, Prophet, Dropzone	Native integration versus cross-platform investigation
CrowdStrike-heavy enterprise	CrowdStrike, Torq, Intezer	Falcon-native automation versus specialized investigation and orchestration
Large heterogeneous SOC	Prophet, 7AI, Torq, Qevlar	Cross-vendor context, agentic investigation, workflow flexibility
Greenfield security program	Exaforce, Palo Alto, SentinelOne	Opportunity to consolidate multiple security functions
Lean SOC with alert backlog	Dropzone, Intezer, Qevlar	Direct emphasis on autonomous triage capacity
MSSP or MDR provider	7AI, Exaforce, Qevlar, Torq	Multi-customer scalability and operational automation

These are evaluation shortlists, not endorsements.
8. How I would evaluate a vendor in a real proof of value
Rather than relying on vendor demonstrations or published accuracy figures, I would require the same blinded investigation workload across shortlisted providers.
Evaluation dimension	What to measure
Detection effectiveness	Missed attacks, especially high-impact incidents
Investigation accuracy	True-positive and false-positive decisions against adjudicated ground truth
Investigation depth	Whether previously unreported evidence and attack relationships are discovered
Autonomous coverage	Percentage of cases completed without intervention, broken down by alert category
Time to investigate	Median and P95 time to a supported verdict
Response safety	Unauthorized actions, unnecessary containment, policy violations
Explainability	Evidence provenance, tool-call history, uncertainty, auditability
Integration quality	Gaps in data access, context retrieval, action execution
Total cost	Licenses, infrastructure, telemetry, model usage, implementation and remaining analyst labor

Critically, I would separately test routine alerts, ambiguous investigations, novel threats, and malicious or misleading content encountered during investigations.

That prevents a vendor with excellent routine triage results from appearing equivalent to one that can genuinely investigate complicated, unfamiliar incidents.

Final competitive assessment
The AI-SOC market presents two viable long-term positions.

Platform ownership: Vendors such as Palo Alto Networks, CrowdStrike, Microsoft, and emerging platform challengers such as Exaforce and 7AI can capture value across telemetry, detection, investigation, and response.

Best-in-class autonomous operations: Vendors such as Prophet, Intezer, and other focused startups can remain valuable by delivering deeper, more reliable, vendor-neutral investigations than customers obtain from their incumbent platforms.

The weakest strategic position is likely to be a standalone product whose only lasting function is classifying and summarizing alerts.

The decisive competitive moat will increasingly be trustworthy autonomous execution over high-quality security context, rather than access to an advanced language model.

For a more focused competitive study, I would prioritize 7AI, Exaforce, Prophet Security, Dropzone AI, Torq, Microsoft, CrowdStrike, and Palo Alto Networks as the core comparison set, then test Intezer and Qevlar where forensic specialization and heterogeneous investigation are especially important.


>if we were to capture essential relevant information and metrics for each company, what would the columns of the CSV be and why?

I recommend a **master CSV with approximately 35–40 columns**, organized around seven dimensions: company identity, product positioning, technical capabilities, autonomy, operational performance, commercial traction, and competitive differentiation.

The objective should be to support three forms of analysis: **comparing product capabilities, evaluating competitive strength, and identifying market opportunities**.

The unit of analysis should be one row per company's primary AI-SOC product. That matters because Microsoft, CrowdStrike, and Palo Alto Networks have multiple security products, and we don't want to conflate company-wide metrics with AI-SOC product metrics.

## **1. Recommended CSV schema**

### **A. Company identity and market positioning**

| Column              | Why it matters                                                                                   |
| ------------------- | ------------------------------------------------------------------------------------------------ |
| `company_name`      | Unique company identifier and primary comparison dimension.                                      |
| `website`           | Link to the company's official website.                                                          |
| `founded_year`      | Helps assess company maturity and startup versus incumbent dynamics.                             |
| `vendor_type`       | Classifies companies as AI-native startup, established security vendor, or acquired/subsidiary.  |
| `ownership_status`  | Public, private, or subsidiary; helps contextualize financial data.                              |
| `ai_soc_product`    | Identifies the actual product being compared, such as Charlotte AI or Dropzone's AI SOC Analyst. |
| `target_segment`    | Enterprise, midmarket, SMB, MSSP, or combinations.                                               |
| `product_category`  | AI analyst overlay, autonomous SOC platform, SIEM/XDR platform, SOAR, or AI-native MDR.          |
| `value_proposition` | One-sentence explanation of the primary customer benefit.                                        |

### **B. Technical architecture and integration**

| Column                 | Why it matters                                                                         |
| ---------------------- | -------------------------------------------------------------------------------------- |
| `deployment_model`     | SaaS, on-premises, hybrid, or managed service.                                         |
| `data_architecture`    | Centralized ingestion, federated querying, or platform-native telemetry.               |
| `integration_count`    | Measures claimed breadth of compatibility, though not integration quality.             |
| `supported_platforms`  | Identifies supported SIEM, EDR, cloud, identity, and ticketing ecosystems.             |
| `deployment_time_days` | Quantifies potential time to value and implementation friction.                        |
| `vendor_neutrality`    | Measures independence from a specific security ecosystem. Use a documented 1–5 rubric. |

### **C. Product capabilities and autonomy**

Rather than storing only yes/no values, I recommend standardized capability levels.

| Column                        | Why it matters                                                                                |
| ----------------------------- | --------------------------------------------------------------------------------------------- |
| `alert_triage_level`          | Measures ability to classify and prioritize incoming alerts.                                  |
| `investigation_level`         | Measures autonomous evidence gathering, correlation, and incident reconstruction.             |
| `threat_hunting_level`        | Captures proactive threat discovery, rather than reactive investigation alone.                |
| `detection_engineering_level` | Tracks rule creation, tuning, and automated detection improvement.                            |
| `response_autonomy_level`     | Distinguishes recommendations, approval-gated actions, and autonomous remediation.            |
| `human_approval_controls`     | Captures operator oversight and control over potentially disruptive actions.                  |
| `evidence_traceability`       | Measures whether conclusions are supported by auditable sources and investigation steps.      |
| `forensic_depth`              | Differentiates basic alert enrichment from deep endpoint, malware, and attack-chain analysis. |

Use a common rubric for the five primary autonomy levels:

| Level | Meaning                                                                          |
| ----- | -------------------------------------------------------------------------------- |
| 0     | Not supported                                                                    |
| 1     | Manual workflow or search assistance                                             |
| 2     | AI-assisted recommendations                                                      |
| 3     | Autonomous execution with human approval                                         |
| 4     | Autonomous execution under defined policies                                      |
| 5     | Closed-loop operation with automated monitoring, corrective action, and controls |

This rubric should only be applied where meaningful; control quality and forensic depth deserve separate definitions.

### **D. Quantitative operational performance**

These are arguably the **most valuable metrics**, but also the hardest to obtain consistently.

| Column                         | Why it matters                                                                                               |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `autonomous_resolution_pct`    | Percentage of cases fully resolved without analyst intervention.                                             |
| `triage_precision_pct`         | Proportion of alerts classified as malicious that are genuinely malicious.                                   |
| `attack_recall_pct`            | Proportion of genuinely malicious cases the system correctly identifies.                                     |
| `median_investigation_minutes` | Measures investigation efficiency.                                                                           |
| `median_response_minutes`      | Measures time from detection to response action.                                                             |
| `benchmark_context`            | Records workload, test environment, number of cases, and methodology needed to interpret performance claims. |

Avoid treating published vendor benchmarks as directly comparable unless they use the same workloads, ground truth, and measurement rules.

For example, a 95% automation claim could describe routine benign alerts rather than serious attack investigations. Both the percentage and its denominator matter.

### **E. Commercial traction and business fundamentals**

| Column                             | Why it matters                                                                       |
| ---------------------------------- | ------------------------------------------------------------------------------------ |
| `pricing_model`                    | Per analyst, per alert, per endpoint, usage-based, platform license, etc.            |
| `estimated_annual_cost_usd`        | Enables normalized cost comparisons for a specified customer workload.               |
| `customer_count`                   | Indicates adoption, ideally for the AI-SOC product rather than the vendor overall.   |
| `annual_recurring_revenue_usd`     | Indicates commercial traction, but must be labeled company-wide or product-specific. |
| `total_funding_usd`                | Relevant to private startups' capitalization and ability to compete.                 |
| `latest_funding_or_financial_date` | Establishes recency of financial information.                                        |

For publicly traded incumbents, funding is generally not comparable to venture funding. Leave it blank where not applicable rather than entering zero.

### **F. Competitive differentiation**

| Column                | Why it matters                                                                                                 |
| --------------------- | -------------------------------------------------------------------------------------------------------------- |
| `key_differentiator`  | Captures why customers might select this vendor over alternatives.                                             |
| `key_limitations`     | Highlights product gaps, ecosystem dependencies, or adoption barriers.                                         |
| `primary_competitors` | Supports competitor network analysis and market clustering.                                                    |
| `competitive_moat`    | Categorizes advantage: proprietary data, integrations, workflow IP, forensic expertise, distribution, or cost. |

### **G. Research provenance and confidence**

| Column               | Why it matters                                                                |
| -------------------- | ----------------------------------------------------------------------------- |
| `product_source_url` | Provides traceable evidence for product capability claims.                    |
| `metrics_source_url` | References the relevant benchmark, report, or test.                           |
| `evidence_quality`   | Distinguishes independently tested findings from vendor claims and estimates. |
| `last_verified_date` | Enables periodic refreshes and detection of stale information.                |

I would use an evidence classification such as `independent_test`, `customer_report`, `vendor_claim`, `analyst_estimate`, or `unknown`.

## **2. Copyable CSV header**

Here is the full proposed schema, ready to use:

**AI-SOC competitive intelligence schema**

&#x20;Copy header

43 columns · One row per company/product · Missing values left blank

Suggested encoding: UTF-8, ISO 8601 dates, numeric fields without currency symbols, and quoted text for values containing commas.

## **3. What I would actually prioritize**

Not all 43 columns are equally important. For an initial competitive intelligence dataset, I would prioritize these dimensions:

Product capabilities and autonomy

30%

Operational performance

25%

Integration and architecture

20%

Commercial traction and pricing

15%

Competitive differentiation

10%

Illustrative research-priority weights, not empirically validated vendor scoring weights. Company identity and source provenance are foundational fields rather than scored dimensions.

These weights favor technical effectiveness and demonstrated customer outcomes over funding announcements or marketing positioning.

## **4. Important data modeling consideration**

I would eventually split the data into three related CSV files instead of keeping everything in one wide table:

**companies.csv**

Identity, ownership, funding, financials, commercial traction, and market positioning

company_id → company_id

**products.csv**

One row per AI-SOC offering, with deployment, capabilities, integration, pricing, and positioning

product_id → product_id

**benchmarks.csv**

Multiple dated evaluations per product, including workload, metrics, provenance, and methodology

This avoids a fundamental problem with the one-row approach: operational performance depends on benchmark date, environment, alert mix, and configuration. A single metric per vendor would obscure that variation.

**My recommendation:** Start with the 43-column master CSV for a broad market scan of the eight core competitors identified earlier. Populate factual product information and evidence links first. Leave unverifiable financial or operational fields blank. Once sufficient benchmark evidence is available, normalize the data into the three-file structure and build a defensible competitive scoring model.

That gives you a useful dataset immediately without sacrificing the ability to perform rigorous longitudinal analysis later.


>build out companies.csv

Created and populated `companies.csv` with researched information for 15 AI-SOC companies.

**companies.csv**

UTF-8 CSV · 17 KB · Verified November 19, 2026

# **15**

Companies

# **46**

Columns

# **8**

Funding figures

Download companies.csv

The dataset includes eight AI-native vendors, six established public vendors, and Cribl as an emerging AI-SOC competitor.

It covers company identity, headquarters, ownership, funding rounds, valuations, revenue, ARR, customer traction, target segments, competitive advantages, risks, and recent developments.

**Data quality safeguards:** Undisclosed values are blank rather than zero; financial metrics have dates and scope definitions; funding amounts distinguish exact figures from lower bounds; and each company has supporting source URLs.

Important: Public-company revenue figures are consolidated corporate revenues, **not AI-SOC product revenues**. These are explicitly labeled in the CSV.

This file is ready to serve as the company dimension for a future `products.csv`, connected by `company_id`.


>build out products.csv

Created `products.csv`, linked to the existing `companies.csv`.

**products.csv**

CSV · 33.8 KB · November 19, 2026

# **33**

Products

# **15**

Companies

# **47**

Columns

Download products.csv

### **What's included**

Each product has structured information covering:

- **Identity:** Product ID, company ID, product family, parent product, and category.
- **Architecture:** Deployment model, data architecture, integration strategy, and security data sources.
- **Capabilities:** 12 indicators including autonomous investigation, threat hunting, detection engineering, response automation, forensics, and governance.
- **Competitive positioning:** Value proposition, differentiation, limitations, and target buyers.
- **Research quality:** Product availability, source URLs, evidence classification, and verification date.

The dataset distinguishes primary AI-SOC platforms from their constituent agents and supporting products. For example, Prophet's SOC Analyst, Threat Hunter, and Detection Engineer are separate records; Microsoft's preview triage agent is distinguished from Security Copilot.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.prophetsecurity.ai\&sz=32)

Prophet Security+2



**Data-quality safeguards:** Missing capabilities are not treated as unsupported, marketing claims are not presented as independently validated performance, and announced products are distinguished from verified generally available offerings.

I also validated that all 33 product IDs are unique, all 15 company IDs match `companies.csv`, and the product-family relationships resolve correctly.

The two CSVs now provide a foundation for a competitive intelligence dataset. The next logical addition is `benchmarks.csv`, containing independently comparable measurements of investigation accuracy, autonomous resolution, response time, and cost.


>build out benchmarks.csv

Created benchmarks.csv and linked it to the existing companies.csv and products.csv datasets.
benchmarks.csv

54.7 KB · 37 columns · Verified November 19, 2026


75
Metric records


15
Companies


33
Products covered



Download benchmarks.csv

What's included
The CSV contains 92 records: 75 quantitative observations and 17 explicit research-gap records.

Metrics include investigation time, automation rates, verdict accuracy, false-positive reduction, response time, analyst-hours saved, throughput, and operational costs.

A few examples from the source material:
Vendor	Reported outcome	Evidence
Dropzone AI	45–61% faster investigations in two scenarios	Vendor-commissioned CSA study  Dropzone AI
Prophet Security	91.9% of investigations resolved automatically in one deployment	Customer case study  Prophet Security
CrowdStrike	Greater than 98% agreement with expert triage decisions	Vendor benchmark  CrowdStrike.com
Splunk	Average handling time fell from 15.4 to 5.6 minutes	Internal SOC evaluation  Splunk
Exaforce	95% reduction in mean investigation time	Vendor-reported aggregate  Exaforce

These measurements are not directly comparable because their workloads, baselines, denominators, and evaluation methods differ.
Data integrity
Every record uses the existing company_id and product_id keys. The dataset also records evaluation context, sample size when disclosed, baseline values, measurement units, source URLs, and evidence independence.

Quantitative evidence was found for products belonging to 14 of the 15 companies. Cribl and several individual product offerings have research-gap records rather than invented performance figures.

The three CSVs now form a relational competitive-intelligence dataset:

companies.csv → products.csv → benchmarks.csv

The next analytical step would be to normalize genuinely comparable metrics and build a competitive scorecard that accounts for evidence quality, rather than simply ranking vendors by their published percentages.


>Plan a data visualization project around these datasets

# **AI-SOC Market Atlas**

Interactive data visualization project plan · November 19, 2026

**Project concept:** Build an interactive competitive-intelligence application that allows users to explore the AI Security Operations Center market, compare startups with established vendors, investigate product capabilities, and critically evaluate published performance benchmarks.

The central question:

> Which AI-SOC vendors are best positioned to deliver autonomous security operations, and what evidence supports their competitive claims?

The application should be built in **VizHub**, using React, TypeScript, and D3, with the three CSV datasets as its initial data sources.

## **1. What the datasets support**

I inspected the actual CSV files. Together they provide:

# **15**

Companies

Startups, incumbents, and challengers

# **33**

Products

Platforms, agents, and services

# **75**

Benchmark observations

Reported quantitative outcomes

# **17**

Evidence gaps

Explicit missing-benchmark records

There are 92 benchmark records in total: 75 metric observations and 17 research-gap records. Every company has one designated primary AI-SOC offering, alongside additional products where applicable.

The dataset naturally forms a three-level hierarchy:

**companies.csv**

Company identity, financials, positioning

**products.csv**

Capabilities, architecture, deployment, market status

**benchmarks.csv**

Measurements, methodology, evidence and sources

### **Intended audience**

The primary audience is cybersecurity buyers, industry analysts, investors, and security product strategists.

The same application should support two complementary modes: an approachable visual overview for a first-time visitor and a detailed research workspace for someone evaluating specific vendors.

## **2. Proposed application structure**

**AI-SOC Market Atlas**

Conceptual wireframe

Explore

Compare

Benchmarks

Company profiles

## **Who is building the autonomous SOC?**

Explore the market, compare capabilities, and examine the evidence.

## **15**

Vendors

## **33**

Products

## **75**

Metrics

Competitive landscape

AI-native

**7AI · Exaforce**

Prophet · Dropzone · Torq

Established platforms

**Microsoft · CrowdStrike**

Palo Alto · Google · Cisco

Interactive positioning view with selectable vendors, tooltips, and links to product evidence

Capability comparison

| Vendor    | Triage | Investigate | Response |
| --------- | ------ | ----------- | -------- |
| 7AI       |        |             |          |
| Dropzone  |        |             |          |
| Microsoft |        |             |          |

Illustrative subset of the documented-capability fields. A dash represents unknown, not unsupported.

This is a multipage exploration experience rather than a single dashboard. Each view should answer a distinct question while preserving the user's current filters and vendor selections.

## **3. Core visualization views**

I recommend four primary views, plus an integrated methodology and evidence-quality panel.

[Using great design to reveal P&L insights and enhance profitability](https://images.openai.com/static-rsc-4/q2h_lJBeOGJz5L5mYbTjoRHHaBSie01xsGi6WBQxp1aUrnIPfFrHS81IrOBac-Ih3btZMGzwpzUSq2nildAK_m2kIJkd10OVEDMUkeksNLMNQZCw2kQkoBjdpnKcmfck5ghzP_BXwP-yBevyYZntmNytrSAWhm0W4NzzVwMzEmc?purpose=inline)

**View 1 — Market landscape**

Show the distribution of AI-native companies, established vendors, and challengers; product categories; and optional funding comparisons for private companies.

**Key interaction:** Select a market segment or vendor to filter the entire application.

[MITRE ATT&CK Framework Explained for Solutions Engineers | it-learn.io](https://images.openai.com/static-rsc-4/1s-qrMtru67B8-NjeJxr2hgDjEhScmPt9jmD538gyiRUjXN56AAeDB4HzjCSw-0f-mnYoeTMMoCOAPTfxPtSq2pyz3wh2jXJLZwwsg0FNQK_Hw2YLtkeBJxhA39vlM8JRP_nbNcKyrdmYBuafHWaSwXMBjGPnladkcl0BExxI6g?purpose=inline)

**View 2 — Capability matrix**

Rows represent products, columns represent capabilities. Documented capabilities use filled cells; missing information uses neutral, unfilled cells. Users can switch between primary offerings and all 33 products.

**Key interaction:** Select two to four products and compare their documented functions side by side.

[Forest-style plot | Flourish](https://images.openai.com/static-rsc-4/qM2xTZ3YDJgvtv9aTIiVXZhB_Ag_TvonNrHQEeCvxgg61cZ0GwkWapWCt8aeKWzHXs11bxIBveoZpsBVS_McAuQAqMSv4MUGrthYLOoZdwF1Cu24mDXC47n9kG3qqbUWGK4xgo7Bia_IrOJ6_J-BJ8L24-QCa4K1zxqb1k8UmFY?purpose=inline)

**View 3 — Benchmark explorer**

Group observations into performance, automation, quality, response, productivity, cost, and other metric categories. Use dot plots or range plots only for measurements with compatible units and definitions.

**Key interaction:** Select an observation to inspect its baseline, sample, methodology, source, and comparability limitations.

[Top 7 Klue Alternatives for Competitive Intelligence](https://images.openai.com/static-rsc-4/1hkvZPGw-6aLoKhTSQ56hAtaE1qcM-u-e1Cz76G6QH8nJ0K1ttQTbV3PPw0Zve2Z767435G-uaZP-SOEw_2dRLsyIhnu7kf8JnbcneyOXWslQgpu9tsdkUhl2AWcCWTexdsV1fs4KnbzN5LZ5bE8YChDvUYn6oBh5vYMckJf_UQ?purpose=inline)

**View 4 — Vendor profile**

Combine identity, ownership, funding, strategic positioning, product hierarchy, documented capabilities, and benchmark evidence into one research page.

**Key interaction:** Follow a specific product to its benchmark evidence or add it to the comparison workspace.

### **Benchmark exploration deserves special attention**

A particularly important finding from the data inspection is that the 75 benchmark observations contain **71 distinct metric names**. Only 16 of the 33 products have at least one quantitative benchmark observation.

Consequently, plotting all benchmark percentages in a common vendor-ranking bar chart would be misleading.

Instead, I propose a benchmark explorer with two modes:

**Evidence gallery:** Browse all published measurements as individually labeled observations, with their original source and context.

**Comparable measurements:** Display a shared quantitative axis only when metric definitions, units, workloads, and baselines are sufficiently compatible.

The first mode will be useful immediately. The second will become more valuable as the research dataset matures.

## **4. Interaction design**

The experience should be driven by coordinated exploration.

Example interactive comparison workflow

Select vendors (up to four)

7AI

Exaforce

Prophet Security

Dropzone AI

Torq

Microsoft

CrowdStrike

Palo Alto Networks

CapabilitiesBenchmarksCompany

Comparison selection preview

2 vendors selected

7AI · CrowdStrike

Compare documented product functions and unknowns.

Explore selected comparison This illustrates the intended multiselection workflow. The full application would implement coordinated charts, not just the selection controls shown here.

Within the finished application, selecting a vendor in the market landscape would highlight its products in the capability matrix, filter relevant evidence in the benchmark explorer, and update the profile panel. Selections should persist through URL query parameters for sharing.

## **5. Evidence quality as a first-class visual dimension**

The most important design decision is to **separate product claims from verified product performance**.

The current dataset has notable limitations:

| Field                                                  | Current coverage | Visualization implication                              |
| ------------------------------------------------------ | ---------------- | ------------------------------------------------------ |
| Quantitative benchmark observations                    | 75               | Show with source and methodological context            |
| Benchmark observations with sample size populated      | 6 of 75          | Highlight limitations in statistical interpretation    |
| Benchmark observations with publication date populated | 7 of 75          | Use verification date separately from publication date |
| Product pricing model populated                        | 1 of 33          | Do not build a meaningful pricing leaderboard yet      |
| Published connector counts populated                   | 0 of 33          | Avoid integration-count rankings                       |
| Deployment time populated                              | 0 of 33          | Treat deployment speed as a research gap               |
| Capability fields                                      | Partial          | Distinguish documented from unknown                    |

Source types are predominantly vendor case studies, claims, or vendor-associated evaluations. That does not invalidate them, but it limits how strongly they support cross-vendor conclusions.

The application should include a visible evidence-quality filter, source links on every benchmark, and explicit methodological warnings for noncomparable measurements.

For the capability matrix, use the actual CSV values dynamically. In the illustrative wireframe above, the response-orchestration cells for 7AI and Microsoft should be marked documented; Dropzone's primary offering has a blank value for that field.

## **6. Technical implementation**

I propose a small, client-side VizHub application without a dedicated backend initially.

**3 static CSV datasets**

**Typed data loading and validation**

Parse CSV · Validate IDs · Preserve missing values

**Normalized client-side data model**

Companies → Products → Benchmarks

**React + TypeScript + D3**

Coordinated views · Cross-filtering · Shared selections

**Published VizHub visualization**

Responsive · Shareable · Embeddable

D3 would handle chart scales, layouts, and SVG rendering primitives. React would manage filters, state, selections, detail panels, and accessibility. The datasets are small enough to load entirely in memory.

I would derive a small number of metrics at runtime, such as the count of documented capabilities, products with quantitative evidence, benchmark observations by source type, and research completeness. These must be presented as *documentation or evidence coverage*, not as objective product-quality scores.

### **Visual design direction**

A clean, editorial data-journalism aesthetic would suit this subject: light background, dark typography, restrained teal and blue accents, and amber for evidence uncertainty.

The application should prioritize legible labels, high-information-density tables, subtle hover interactions, and responsive layouts. Avoid cybersecurity-themed neon effects or animated network backgrounds that compete with the data.

## **7. Incremental implementation plan**

I recommend five independently reviewable PR-sized workstreams.

| Phase                         | Deliverable                                                                                  | Acceptance criteria                                                                                                          |
| ----------------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **PR1 — Data foundation**     | CSV ingestion, typed schemas, relationship validation, normalized selectors, sample fixtures | All 15 company IDs, 33 product IDs, and 92 benchmark references validate. Missing data and numeric qualifiers are preserved. |
| **PR2 — Market landscape**    | Overview, vendor segmentation, product composition, interactive company selector             | All companies represented; filters and selections work across desktop and mobile                                             |
| **PR3 — Capability explorer** | Product capability heatmap, hierarchy expansion, multivendor comparison                      | Unknowns are never presented as unsupported; primary and child products remain distinct                                      |
| **PR4 — Benchmark explorer**  | Metric-family filters, dot/range plots, evidence details, source drilldown                   | Heterogeneous measurements cannot accidentally be ranked on one quantitative scale                                           |
| **PR5 — Profiles and polish** | Vendor profiles, URL state, evidence panel, accessibility, responsive testing, publication   | Complete navigation, keyboard accessibility, validated source links, and usable mobile layouts                               |

Each PR should target the main branch directly, with appropriate unit tests for transformation logic and browser-level tests for critical interactions.

## **8. Suggested scope for the first release**

## **MVP: The AI-SOC competitive landscape**

The first release should prioritize useful analysis over feature breadth.

Market overview and company segmentation

Product capability heatmap

Vendor comparison (up to four)

Benchmark evidence explorer

Company/product detail panels

Evidence provenance and missingness

Competitive scoring and weighted rankings

Historical market trends

Automated data refresh and enrichment

Generate specification for selected scope&#x20;

A composite competitive score and longitudinal trends should remain future work. The existing dataset does not yet have enough standardized benchmarks, reliable deployment economics, or dated historical snapshots to support those responsibly.

## **9. What would make this project distinctive?**

The differentiating feature should be **claim-to-evidence exploration**.

A visitor could start with an assertion such as "AI-native vendors deliver faster investigations," select a company, see its supporting performance claim, follow it to the original case study, inspect the test population and baseline, and decide how much confidence to place in it.

This transforms the visualization from a vendor directory into a transparent research tool.

**Recommended final deliverable:** A polished, public-facing VizHub application called *AI-SOC Market Atlas*, with an interactive competitive landscape, capability comparisons, benchmark evidence explorer, and individual company profiles. The initial release should focus on making the existing evidence accessible and trustworthy, not on declaring a winner.
