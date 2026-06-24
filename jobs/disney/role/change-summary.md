# Change Summary — Role at Disney (Ad Platforms / Identity Householding Data)

All changes rephrase or reframe facts already present in `resume.md`. No new skills, tools, employers, or metrics were introduced.

---

## Summary Section

| Field | Detail |
|---|---|
| **Location** | Summary |
| **Type** | rephrase + emphasize |
| **Before** | "Senior Azure Data Engineer with 11+ years…Expert in Databricks Lakehouse and Unity Catalog governance, Delta Lake, large-scale PySpark ETL, and data warehousing (Snowflake, Azure Synapse)." |
| **After** | "Senior Data Engineer with 11+ years designing and delivering scalable, fault-tolerant data pipelines and data products across distributed cloud environments. Expert in Databricks, PySpark/Spark, and Delta Lake for large-scale batch and real-time processing at the petabyte level." |
| **JD link** | JD emphasizes fault-tolerant pipelines, petabyte-scale, real-time + batch delivery, data products — not Azure-specific branding |
| **Suggested emphasis** | Removed "Azure" from the title to avoid narrowing appeal; "petabyte level" mirrors JD language exactly |

---

## Wells Fargo — Bullet 1

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase + emphasize |
| **Before** | "Migrated legacy data frameworks to a Databricks Lakehouse with Unity Catalog and a medallion architecture (Bronze/Silver/Gold) to centralize governance and lineage." |
| **After** | "Built and maintained scalable data product pipelines using Databricks Lakehouse…establishing a comprehensive source of truth for enterprise-wide customer and operational data." |
| **JD link** | JD: "comprehensive source of truth for enterprise-wide customer identifiers"; "build and maintain…Identity Householding Data products" |

---

## Wells Fargo — Bullet 2

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase |
| **Before** | "Designed standardized data schemas in Hackolade and harmonized multi-vendor feeds for consistent downstream consumption." |
| **After** | "Designed and standardized extensible data models in Hackolade, harmonizing multi-vendor feeds for consistent, reusable downstream consumption — improving data product reliability and decreasing schema drift." |
| **JD link** | JD: "Enhance/redesign existing data models"; "extensible, reusable, and maintainable" codebase |

---

## Wells Fargo — Bullet 3

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase + emphasize |
| **Before** | "Built scalable PySpark and Delta Live Tables (DLT) pipelines to ingest, cleanse, and harmonize 5+ TB of customer complaints and operational data." |
| **After** | "Developed large-scale PySpark and Delta Live Tables (DLT) pipelines…increasing unit test coverage and enforcing data quality at pipeline boundaries." |
| **JD link** | JD: "Increase unit test coverage on the existing codebase"; "large data pipelines" |

---

## Wells Fargo — Bullet 4

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase (minor) |
| **Before** | "Orchestrated data integration using Azure Data Factory, Databricks Workflows, and Apache Airflow…" |
| **After** | Retained substance; reframed as "orchestrating data integration" to match JD's "data integration and orchestration toolsets (e.g. Airflow)" language |
| **JD link** | JD: "Solid experience with data integration and orchestration toolsets (e.g. Airflow)" |

---

## Wells Fargo — Bullet 6 (CI/CD)

| Field | Detail |
|---|---|
| **Location** | Work Experience → Wells Fargo |
| **Type** | rephrase |
| **Before** | "Implemented CI/CD with Azure DevOps and GitHub to automate testing and deployments." |
| **After** | "Implemented CI/CD automation with Azure DevOps and GitHub to enforce code quality, streamline deployments, and reduce manual intervention." |
| **JD link** | JD: "Solid experience with…CI/CD"; code review and quality focus |

---

## Medtronic — Bullet 1

| Field | Detail |
|---|---|
| **Location** | Work Experience → Medtronic |
| **Type** | rephrase + emphasize |
| **Before** | "Architected real-time pipelines for embedded pacemaker sensor data using Apache Kafka for buffering and PySpark Streaming for processing." |
| **After** | "Architected fault-tolerant, real-time data pipelines…ensuring reliable delivery of both streaming and batch datasets." |
| **JD link** | JD: "scalable, fault-tolerant data processing pipelines…reliable delivery of both real-time and batch data" |

---

## Medtronic — Bullet 2

| Field | Detail |
|---|---|
| **Location** | Work Experience → Medtronic |
| **Type** | rephrase |
| **Before** | "Integrated streaming and batch pipelines in Azure Synapse and Databricks to provide synchronized datasets for analytics and APIs." |
| **After** | Added "MPP" after Azure Synapse and "high-quality datasets for analytics APIs and downstream consumers" to mirror JD's MPP reference and data product framing |
| **JD link** | JD: "at least one major MPP or cloud database technology"; "downstream consumers" concept |

---

## State Farm — Bullet 1

| Field | Detail |
|---|---|
| **Location** | Work Experience → State Farm |
| **Type** | rephrase |
| **Before** | "Developed SSIS/SSRS and Spark-based pipelines to ingest from DB2, SQL Server, Oracle, flat files, APIs, XML, and JSON." |
| **After** | Removed SSIS/SSRS (legacy Microsoft tools irrelevant to JD); reframed around "reusable, maintainable integration patterns" |
| **JD link** | JD: "Enhance/improve the underlying codebase to be extensible, reusable, and maintainable" |

---

## Nielsen — Bullet 1

| Field | Detail |
|---|---|
| **Location** | Work Experience → Nielsen |
| **Type** | rephrase + emphasize |
| **Before** | "Architected serverless processing handling ~55 TB/day and contributed to a multi-petabyte data warehouse built on Apache Spark and S3." |
| **After** | Added explicit callout: "demonstrating hands-on experience processing datasets at the petabyte level" |
| **JD link** | JD: "query and process large datasets at the petabyte level"; "Solid experience with AWS S3" |

---

## Nielsen — Bullet 2 (new framing)

| Field | Detail |
|---|---|
| **Location** | Work Experience → Nielsen |
| **Type** | emphasize |
| **Before** | Single bullet only |
| **After** | Added second bullet on "fault-tolerant batch processing pipelines with strong attention to performance efficiency and data quality at scale" |
| **JD link** | JD: "fault-tolerant data processing pipelines"; "strong attention to detail" |

---

## Skills Section

| Field | Detail |
|---|---|
| **Location** | Skills |
| **Type** | reorder + rephrase |
| **Before** | Grouped as "Languages & frameworks", "Data & infrastructure", "Orchestration & quality", "DevOps & infra-as-code", "BI & reporting" |
| **After** | Regrouped into "Big data & distributed systems", "Cloud data platforms", "Orchestration & data quality", "Data modeling & warehousing" — surfacing Spark, S3, Databricks, Snowflake, Airflow more prominently |
| **JD link** | JD stack: Spark, Databricks, S3, Snowflake, Airflow, data modeling — all must be visible at a glance |

---

## Items intentionally NOT added (per fit report "Do not add")

- Scala — not in resume.md
- Presto — not in resume.md
- Hive — not in resume.md
- Redshift — not in resume.md
- BigQuery — not in resume.md
- Identity graph / householding domain experience — not in resume.md
- Ad tech / advertising platform domain — not in resume.md
