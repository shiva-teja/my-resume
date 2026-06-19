# Fit Report — Role at Disney (Ad Platforms / Identity Householding Data)

## Overall fit

**Tier:** Strong
**Verdict:** Good fit - apply with the tailored resume

Karthik's 11+ years of big data engineering experience maps cleanly to Disney's core requirements: petabyte-scale distributed processing (Spark/PySpark), Databricks, Snowflake, S3, Airflow, real-time and batch pipelines, CI/CD, and data modeling. His production operations experience at Wells Fargo and Medtronic demonstrates the SME/on-call accountability the JD requires. The only notable technical gap is Scala — the JD lists Scala/Spark alongside Python, and Karthik's background is Python/PySpark only. This is unlikely to be a dealbreaker given the depth of coverage across all other requirements, but he should be prepared to speak to it honestly.

---

## Strong matches

| JD Requirement | Evidence in resume.md |
|---|---|
| 5+ years big data engineering, large data pipelines | 11+ years total; Senior Data Engineer roles across Wells Fargo, Medtronic, State Farm, Centene, Nielsen |
| Distributed systems — Databricks compute, Spark | Databricks Lakehouse, Delta Live Tables, PySpark ETL across multiple roles; Databricks Certified (Associate & Professional) |
| Python and SQL skills processing big datasets | Python and PySpark explicitly listed; SQL/T-SQL across all roles |
| Cloud database technology — Snowflake, Databricks | Snowflake and Databricks listed in skills; Azure Synapse (MPP) also covered |
| Petabyte-scale data processing | Nielsen: ~55 TB/day serverless processing, multi-petabyte data warehouse on Spark + S3 |
| Real-time and batch pipeline delivery | Medtronic: Kafka + PySpark Streaming (real-time); Wells Fargo: medallion architecture batch pipelines |
| Data modeling and data warehousing practices | Hackolade schema design, medallion (Bronze/Silver/Gold) architecture, WellCare and Truist DW roles |
| Orchestration — Airflow, CI/CD | Airflow (listed), Azure DevOps CI/CD, GitHub, YAML pipelines across multiple roles |
| AWS S3 | S3 in skills; Nielsen multi-petabyte warehouse on Spark + S3 |
| Operational experience as SME in production environments | Wells Fargo compliance reporting, Medtronic pacemaker telemetry pipelines — production on-call context implied |
| Code quality, unit testing, extensible/maintainable codebase | CI/CD with automated testing at Wells Fargo and State Farm; Delta Live Tables quality framework |
| Agile (Scrum, Kanban) participation | Implied through squad/cross-functional collaboration across enterprise roles |
| Bachelor's / Master's in CS or equivalent | MS Computer Science — Stevens Institute of Technology |

---

## Gaps

- **Scala:** JD explicitly lists "Python, Scala/Spark." Karthik's resume lists Python/PySpark only. Scala is absent. He should confirm whether he has any Scala familiarity not listed; otherwise this is a gap to disclose if asked.
- **Presto / Hive:** JD mentions these as Databricks-adjacent query tools. Neither appears in the resume.
- **Identity / Device data products, Householding concepts:** The specific domain (identity graphs, device-to-household linkage, customer identifier management) is not represented. Karthik should study the domain to speak credibly in interviews.
- **Ad Tech context:** Disney's Ad Platforms org context (advertising performance, identity for targeting) is not part of the candidate's background — healthcare, finance, and telecom are the domains. Not a hard disqualifier, but worth acknowledging.

---

## Do not add

The following JD items have **no support** in `resume.md` and must **not** appear in `tailored-resume.md`:

- Scala (language)
- Presto (query engine)
- Hive (query engine)
- Redshift (not in resume — Snowflake and Synapse are)
- BigQuery (not in resume)
- Identity householding / identity graph architecture experience
- Ad tech / advertising data product domain experience
