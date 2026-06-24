# Fit Report — Role at Company (Disney Ad Platforms / Identity Householding)

## Overall fit

**Tier:** Strong  
**Verdict:** Good fit - apply with the tailored resume

Karthik's 11+ years of big data engineering, expert-level Databricks/PySpark/Spark experience, petabyte-scale pipeline history (Nielsen ~55 TB/day), AWS S3 background, Airflow orchestration, Snowflake, and robust CI/CD track record align directly with virtually every must-have in this JD. The only meaningful gap is the absence of Scala and explicit Hive/Presto usage — areas mitigated by deep PySpark/Spark equivalency. The identity/ad-tech domain is new but the core engineering skills are a clear match. Apply with the tailored resume.

---

## Strong matches

| JD Requirement | Resume Evidence |
|---|---|
| 5+ years big data engineering | 11+ years across Wells Fargo, Medtronic, Nielsen, State Farm, and more |
| Distributed systems / Databricks / Spark at petabyte scale | Nielsen: ~55 TB/day serverless processing, multi-petabyte data warehouse on Spark & S3; Databricks Certified (Associate & Professional) |
| Python and SQL for big data processing | Python/PySpark/SQL used across all roles; primary processing language throughout |
| AWS S3 experience | Nielsen role: multi-petabyte data warehouse built on Apache Spark and S3 |
| MPP / cloud database technology (Snowflake, Databricks) | Snowflake listed in skills; Databricks Lakehouse used at Wells Fargo |
| Data modeling and data warehousing methodologies | Schema design in Hackolade at Wells Fargo; medallion architecture (Bronze/Silver/Gold); data warehouse developer roles at WellCare and Truist |
| Real-time and batch data pipelines | Medtronic: Kafka + PySpark Streaming (real-time); all roles include batch pipelines |
| Airflow orchestration and CI/CD | Airflow at Wells Fargo; CI/CD with Azure DevOps and GitHub across multiple roles |
| Fault-tolerant, scalable data processing pipelines | Delta Live Tables, medallion architecture, Kafka buffering for reliability |
| Operational SME / on-call production environment | Wells Fargo compliance pipelines; Medtronic patient-data telemetry; multi-system production experience |
| Agile / Scrum / Kanban participation | Implied through sprint-based delivery across enterprise roles (Wells Fargo, Medtronic) |
| Code reviews and problem-solving | CI/CD-gated review process described across Wells Fargo and State Farm |
| Extensible, reusable, maintainable codebase / unit test coverage | Rewrote legacy SQL into optimized Spark/dbt transformations; standardized schemas and pipelines |
| Bachelor's/Master's in CS or equivalent | M.S. Computer Science, Stevens Institute of Technology |

---

## Gaps

| Gap | Honest Mitigation |
|---|---|
| **Scala/Spark** — JD lists Scala as a required language | No Scala on resume. However, 8+ years of PySpark/Spark (same execution engine, same APIs) makes this transferable. Candidate should be transparent and frame PySpark expertise as primary; Scala is learnable given deep Spark knowledge. |
| **Hive / Presto** — explicitly named in JD | Not mentioned on resume. Presto/Hive are SQL-on-Hadoop tools; candidate has extensive SQL, Spark SQL, and Snowflake — functionally adjacent. Cannot claim these without evidence. |
| **Identity / Householding / Ad-tech domain** — JD is specifically for ad identity data products | No ad-tech or identity graph domain experience on resume. Healthcare (Medtronic, Centene, WellCare), finance (Wells Fargo, Truist), and telecom (Nielsen) experience demonstrates enterprise-scale data with strong identity/governance parallels (Unity Catalog, PII compliance). |
| **Databricks compute specifically named as the distributed system** — JD says "Databricks compute using Spark, Presto, Hive" | Resume shows Databricks broadly (Lakehouse, DLT, Workflows) but Presto/Hive not explicitly on Databricks. Strong overall Databricks depth partially bridges this. |

---

## Do not add

The following JD items have **no support** in `resume.md` and must not appear in `tailored-resume.md`:

- **Scala** — candidate works exclusively in Python/PySpark; do not list Scala as a skill or imply Scala experience
- **Hive** — not mentioned anywhere in resume; do not add
- **Presto** — not mentioned anywhere in resume; do not add
- **Ad identity / device identity / householding domain knowledge** — no advertising or identity graph background; do not add
- **Scrumban** — Agile participation is implied but Scrumban is not specifically evidenced; do not list as a named methodology

---

## Searchability checklist

- [x] Title match: "Senior Data Engineer" — present in resume and tailored version
- [x] Core stack named: Databricks, Spark, PySpark, Python, SQL, Airflow, S3, Snowflake, Delta Lake
- [x] Years of experience visible: "11+ years" in summary
- [x] Petabyte-scale keyword: surfaced from Nielsen role
- [x] Real-time + batch: both present
- [ ] Scala: intentionally omitted (not supported)
- [ ] Hive / Presto: intentionally omitted (not supported)
