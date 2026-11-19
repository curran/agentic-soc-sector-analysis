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

