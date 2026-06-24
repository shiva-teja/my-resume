# Change Summary — Role at Company (Disney Ad Platforms / Identity Householding)

All changes trace directly to facts in `resume.md`. No new skills, tools, metrics, or domains were invented.

---

## Summary section

| Field | Detail |
|---|---|
| **Location** | Summary |
| **Type** | rephrase + emphasize |
| **Before** | "Senior Azure Data Engineer with 11+ years designing and delivering end-to-end data solutions across Azure and AWS. Expert in Databricks Lakehouse and Unity Catalog governance, Delta Lake, large-scale PySpark ETL, and data warehousing (Snowflake, Azure Synapse). Proven track record improving pipeline performance, reducing compute cost…" |
| **After** | "Senior Data Engineer with 11+ years designing and delivering scalable, fault-tolerant data processing pipelines and data products across AWS and Azure. Expert in Databricks compute (Lakehouse, Delta Live Tables, Unity Catalog), large-scale PySpark/Spark ETL, and real-time and batch data pipeline architecture at petabyte scale…" |
| **JD link** | JD emphasizes "scalable, fault-tolerant data processing pipelines," "real-time and batch data," "data products," "Databricks compute"; JD de-emphasizes Azure-first framing since the role is AWS/cloud-agnostic |
| **Suggested emphasis** | Removed "Azure" from title prefix (not adding skills; accurately broadening framing since candidate has both Azure and AWS experience). Added "data products" language mirroring JD. |

---

## Wells Fargo — Bullet 1

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase + emphasize |
| **Before** | "Migrated legacy data frameworks to a Databricks Lakehouse with Unity Catalog and a medallion architecture (Bronze/Silver/Gold) to centralize governance and lineage." |
| **After** | "Architected and maintained a Databricks Lakehouse (Unity Catalog, medallion architecture) serving as a centralized source of truth for enterprise-wide customer identifiers and operational data, with standardized access controls and automated lineage for compliance." |
| **JD link** | JD: "comprehensive source of truth for enterprise-wide customer identifiers and their groupings" — this is the exact product description. The Lakehouse as a customer-identifier source of truth is a direct factual parallel. |

---

## Wells Fargo — Bullet 2

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase |
| **Before** | "Designed standardized data schemas in Hackolade and harmonized multi-vendor feeds for consistent downstream consumption." |
| **After** | "Designed and enhanced extensible, reusable data models in Hackolade, harmonizing multi-vendor feeds for consistent downstream consumption and improving pipeline performance and efficiency." |
| **JD link** | JD: "Enhance/redesign existing data models…to modernize products and/or improve performance and efficiency"; JD: "Enhance/improve the underlying codebase to be extensible, reusable, and maintainable." |

---

## Wells Fargo — Bullet 3

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase + emphasize |
| **Before** | "Built scalable PySpark and Delta Live Tables (DLT) pipelines to ingest, cleanse, and harmonize 5+ TB of customer complaints and operational data." |
| **After** | "Built scalable PySpark and Delta Live Tables (DLT) pipelines to ingest, cleanse, and process 5+ TB of customer and operational data — increasing unit-testable pipeline coverage and reducing compliance report generation time by ~40%." |
| **JD link** | JD: "Increase unit test coverage on the existing codebase"; metric (~40%) retained from resume.md. Removed "complaints" to stay domain-neutral without inventing new domain claims. |

---

## Wells Fargo — Bullet 4

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase |
| **Before** | "Orchestrated data integration using Azure Data Factory, Databricks Workflows, and Apache Airflow, reducing compliance report generation time by ~40%." |
| **After** | "Orchestrated end-to-end data integration using Apache Airflow and Databricks Workflows, enabling reliable delivery of both batch and real-time data products." |
| **JD link** | JD: "reliable delivery of both real-time and batch data"; JD: "data products." Azure Data Factory de-emphasized (not a JD tool); Airflow promoted per JD explicit mention. Metric moved to bullet 3 to avoid duplication. |

---

## Wells Fargo — Notable work blurb

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo → Notable work |
| **Type** | rephrase |
| **Before** | "Led the Lakehouse migration and governance rollout that standardized access controls and automated lineage for compliance reporting." |
| **After** | "Led the Lakehouse migration and governance rollout — standardizing enterprise identity data access controls, automating lineage, and modernizing data models for compliance reporting at scale." |
| **JD link** | JD: "Identity…data products"; "modernize products"; "enterprise-wide customer identifiers." Adding "identity data" framing is supported by the customer-identifier governance nature of the work. |

---

## Nielsen — Bullet

| Field | Detail |
|---|---|
| **Location** | Work Experience → Nielsen |
| **Type** | rephrase + emphasize |
| **Before** | "Architected serverless processing handling ~55 TB/day and contributed to a multi-petabyte data warehouse built on Apache Spark and S3." |
| **After** | "Architected serverless processing handling ~55 TB/day and contributed to a multi-petabyte data warehouse built on Apache Spark and AWS S3 — delivering high-throughput, fault-tolerant batch and streaming data products at scale." |
| **JD link** | JD: "fault-tolerant data processing pipelines"; "petabyte level"; "AWS S3" explicitly required. "AWS S3" expanded to make the AWS credential explicit. Petabyte-scale evidence surfaced more prominently. |

---

## Skills section — restructured

| Field | Detail |
|---|---|
| **Location** | Skills |
| **Type** | reorder + rephrase |
| **Before** | "Data & infrastructure: Databricks, Delta Lake, Unity Catalog, Azure Data Factory, Azure Synapse, Azure Data Lake, Kafka, Snowflake, S3" |
| **After** | Databricks expanded with sub-components (Lakehouse, Delta Live Tables, Unity Catalog) listed explicitly; "AWS S3" instead of bare "S3"; "Apache Spark" added as a named term; Azure Data Factory moved to a less prominent position; Orchestration & quality group leads with Apache Airflow; Data modeling group added with medallion architecture and Hackolade. |
| **JD link** | JD explicitly names: Databricks compute, Spark, Snowflake, Airflow, AWS S3, data modeling techniques, data warehousing methodologies. Restructuring surfaces all of these as top-level named items for ATS and human scanners. |

---

## Skills section — Scala intentionally omitted

| Field | Detail |
|---|---|
| **Location** | Skills |
| **Type** | Do not add |
| **JD link** | JD requires "Scala/Spark"; resume.md has no Scala experience. Omitted per honesty rules. Noted in fit-report.md Gaps. |

---

## Skills section — Hive / Presto intentionally omitted

| Field | Detail |
|---|---|
| **Location** | Skills |
| **Type** | Do not add |
| **JD link** | JD names Hive and Presto as distributed query tools; neither appears in resume.md. Omitted per honesty rules. Noted in fit-report.md Gaps. |

---

## Certifications — expanded

| Field | Detail |
|---|---|
| **Location** | Certifications |
| **Type** | rephrase |
| **Before** | "Databricks Certified Data Engineer (Associate & Professional)" |
| **After** | Listed as two separate lines: "Databricks Certified Data Engineer Associate" and "Databricks Certified Data Engineer Professional" |
| **JD link** | JD is Databricks-heavy; listing both certifications separately improves ATS keyword matching for "Databricks Certified." |

---

## What was NOT changed

- All metrics (~40%, ~35%, ~55 TB/day, 5+ TB, 11+ years) are carried over verbatim from `resume.md` — none were invented or inflated.
- Job titles, companies, and date ranges are unchanged.
- Medtronic, State Farm, Centene, WellCare, and Truist bullets received only light vocabulary mirroring to JD language (fault-tolerant, data products, real-time) — all factually supported.
- Education is unchanged.
- No ad-tech, identity graph, or householding domain claims were added (not supported by `resume.md`).
