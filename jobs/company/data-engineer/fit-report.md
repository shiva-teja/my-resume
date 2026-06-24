# Fit Report — Data Engineer at Company

## Overall fit

**Tier:** Strong
**Verdict:** Good fit - apply with the tailored resume

Karthik's 11+ years of data engineering experience substantially exceed the 2+ year requirement, and his real-world work covers every core must-have in this JD: Python/SQL ETL pipelines, Spark/Hadoop-based ingestion, XML/JSON/relational source handling, Airflow orchestration, Git-based CI/CD, data validation, and cross-functional stakeholder communication. The only notable gap is R (listed as preferred, not required), which is easily addressed in a cover note. The resume should be positioned around data pipeline delivery, multi-source ingestion, and Agile/collaborative development practices to mirror the JD's language.

---

## Strong matches

| JD Requirement | Evidence in resume.md |
|---|---|
| 2+ years relevant experience | 11+ years across Wells Fargo, Medtronic, State Farm, Centene, Nielsen, and others |
| Bachelor's / advanced degree in CS or related | M.S. Computer Science, Stevens Institute of Technology |
| Python and SQL | Named explicitly in Skills; used across all roles in PySpark ETL, dbt, and transformations |
| Ingesting from relational DBs, Hadoop/Spark, XML, JSON | State Farm: "ingest from DB2, SQL Server, Oracle, flat files, APIs, XML, and JSON"; Nielsen: Apache Spark + S3 multi-petabyte warehouse |
| ETL — metadata management and data validation | Unity Catalog lineage/governance (Wells Fargo); Great Expectations in Skills; data validation bullets across multiple roles |
| Linux and Git / GitHub | GitHub named in Skills and Wells Fargo CI/CD bullet; Azure DevOps YAML pipelines throughout |
| Automation tools — Airflow | Airflow named in Skills and orchestration bullet at Wells Fargo |
| AWS S3 exposure | Nielsen: "multi-petabyte data warehouse built on Apache Spark and S3"; S3 listed in Skills |
| Real-time modeling solutions ingested into front-end systems | Medtronic: "Built REST APIs exposing aggregated telemetry for patient-facing dashboards" |
| Data lineage and source suitability | Wells Fargo: Unity Catalog automated lineage; Hackolade schema design for multi-vendor feeds |
| Cross-functional stakeholder communication | Centene: partnered with DevSecOps; Wells Fargo: multi-vendor coordination; Medtronic: APIs for clinical teams |
| Reproducible code artifacts and documentation via GitHub | "Implemented CI/CD with Azure DevOps and GitHub to automate testing and deployments" |
| Exploratory data analysis / null & duplicate checks | Great Expectations data quality tool; data cleansing pipelines at Wells Fargo and Centene |
| Agile / continuous delivery mindset | CI/CD across all recent roles; Databricks Workflows + Airflow continuous pipeline delivery |

---

## Gaps

| Gap | Honest mitigation |
|---|---|
| **R (preferred language)** | R is not present in resume.md. Karthik has deep Python/PySpark experience (11+ years) which covers the same analytical workloads. Can be noted in a cover letter as a learning goal. |
| **Autosys / Cron** (named as automation tool examples) | Not explicitly listed; however, Airflow and Azure Data Factory orchestration are direct equivalents and are well-evidenced. |
| **EMR specifically** | AWS EMR not named; however, Spark-on-S3 work at Nielsen is architecturally equivalent. |

---

## Do not add

The following JD items have **no traceable support** in resume.md and must not appear in the tailored resume:

- **R language** — not present anywhere in resume.md
- **Autosys** — not mentioned; do not list as a known tool
- **Cron** — not mentioned; do not list as a known tool
- **AWS EMR** — not explicitly named; do not claim EMR experience
- **Hadoop (as a named technology)** — resume references Spark but not Hadoop/HDFS directly; do not claim standalone Hadoop expertise

---

## Searchability checklist

- [x] Title "Data Engineer" appears in tailored resume
- [x] Core stack named: Python, SQL, PySpark, Airflow, Spark, S3, Git/GitHub
- [x] 11 years of experience visible in Summary
- [x] ETL, data pipelines, data validation keywords present
- [x] AWS S3 surfaced from Nielsen role
