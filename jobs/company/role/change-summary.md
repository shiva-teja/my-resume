# Change Summary — Role at Company

All changes are reframings of real experience from `resume.md`. No new skills, tools, metrics, or domains were invented.

---

## Headline / Title

| Change | Reason |
|---|---|
| Changed title from "Senior Azure Databricks Data Engineer" to "Senior Databricks Data Engineer" | JD does not mention Azure specifically; removing the cloud qualifier broadens relevance and mirrors JD language ("Databricks data engineer") |

---

## Professional Summary

| Change | Reason |
|---|---|
| Added "production-grade data pipelines" phrasing | Direct mirror of JD: "designing and building production-grade data pipelines on Databricks" |
| Added "Deep hands-on expertise with Apache Spark (PySpark and Spark SQL)" | JD lists this as a top requirement; was implicit in original; now explicit up front |
| Added "Delta Lake, including ACID transactions, data versioning" | JD requirement: "Advanced knowledge of Delta Lake, including ACID transactions and data versioning" — evidence exists at Wells Fargo |
| Added "multi-hop medallion architectures (Bronze/Silver/Gold)" | JD requirement: "Proven experience implementing multi-hop architectures" — directly supported by Wells Fargo bullet |
| Added "Expert-level Python and SQL applied to scalable data transformations" | JD requirement: "Expert-level SQL and Python, with a focus on scalable data transformations" — mirrors JD language exactly |
| Added "optimizing data workloads for performance and cost efficiency" | JD requirement: "Experience optimizing data workloads for performance and cost efficiency" — supported by 35% / 30% metrics |
| Added "monitoring, observability, and error handling" | JD requirement: "Demonstrated ability to implement monitoring, observability, and error handling" — supported by Medtronic bullet |
| Added "regulated environments with strict security requirements (GDPR, HIPAA, banking)" | JD requirement: "Experience working in regulated environments with strict security requirements" |
| Added "data quality frameworks (Great Expectations)" | JD requirement: "Familiarity with data quality frameworks and automated validation" |
| Added "test-driven development" and "Agile/Scrum" references | JD requirement: "Experience working on Agile / Scrum teams" — supported by Centene |
| Added "large, complex enterprise systems" | JD requirement: "Meaningful experience working on large, complex systems" |
| Removed "Snowflake, Azure Data Factory, and Power BI delivery" from summary | These are supporting tools, not JD-critical; space used for higher-priority JD terms |

---

## Core Technical Skills Table

| Change | Reason |
|---|---|
| Added "Multi-hop Medallion (Bronze/Silver/Gold), ACID transactions, data versioning" as a named Architecture row | JD calls out these specifically; surfacing them in skills ensures ATS keyword match |
| Added "Great Expectations, Matillion, SonarQube, Azure Monitor, Nagios, Prometheus" to a dedicated "Data Quality & Observability" row | JD requires monitoring/observability and data quality frameworks; these were buried in role bullets |
| Restructured skills table with JD-aligned row labels (e.g., "Databricks & Spark", "Data Architecture", "Data Quality & Observability") | Improves scannability and keyword density for JD priorities |

---

## Wells Fargo (Most Recent Role)

| Change | Reason |
|---|---|
| Rewrote opening bullet to lead with "production-grade Databricks Lakehouse" and "multi-hop medallion architecture (Bronze/Silver/Gold)" | JD top requirements; these are the most important matches and should appear first |
| Added "Delta Lake ACID transactions and data versioning" language to pipeline bullet | JD requirement mirror; fact supported by Delta Lake/Delta Live Tables usage in original |
| Added explicit "automated data quality validation using Great Expectations" bullet | JD: "data quality frameworks and automated validation"; Great Expectations was in original but buried — promoted to standalone bullet |
| Added "schema and business-rule checks before data is promoted between medallion layers" phrasing | Clarifies how data quality integrates with multi-hop architecture — supported by original bullet language |
| Added "improving scalability" to DBT/Spark transformation bullet | JD: "scalable data transformations" — supported by context of re-engineering legacy SQL |
| Added "dev, staging, and production environments" to CI/CD bullet | Clarifies production-grade deployment discipline; implied by "zero-downtime deployments" in original |
| Reordered bullets: medallion architecture → Delta Lake pipelines → data quality → optimization → orchestration → schema design → CI/CD | Ordered by JD priority: architecture first, then data quality, then tooling |

---

## Medtronic Role

| Change | Reason |
|---|---|
| Changed title from "Senior Azure Engineer — Data" to "Senior Data Engineer" | Cleaner title; mirrors JD language; removes Azure-specific label that doesn't match JD vocabulary |
| Added "operating in a strict HIPAA-regulated environment" to the Kafka/streaming bullet | JD: "regulated environments with strict security requirements" — Medtronic is healthcare, this is factual |
| Added standalone "monitoring, observability, and alerting" bullet leading with Azure Monitor, Nagios, Prometheus | JD: "Demonstrated ability to implement monitoring, observability, and error handling" — was buried in original; promoted to first non-pipeline bullet |
| Added "full pipeline visibility and proactive error detection across distributed systems" | JD: "Ability to debug and resolve issues in distributed systems" — supported by monitoring tooling |
| Reordered bullets: PySpark pipelines → real-time data services → monitoring → data governance → security → CI/CD | JD priorities: core pipeline work first, then observability, then governance/security |

---

## State Farm Role

| Change | Reason |
|---|---|
| Changed "Tuned Apache Spark jobs" bullet to lead with "Optimized Apache Spark workloads for performance and cost efficiency" | JD language mirror: "Experience optimizing data workloads for performance and cost efficiency" |
| Added "enforcing infrastructure-as-code discipline" to Terraform bullet | JD: "software engineering principles applied to data systems" — IaC is a software engineering discipline; supported by Terraform usage |
| Reordered bullets: end-to-end pipelines → streaming → optimization → infrastructure → CI/CD | JD priority: core pipelines and optimization above infra tooling |

---

## Centene Role

| Change | Reason |
|---|---|
| Added "ensuring correctness and ownership over every deliverable" to Agile/TDD bullet | JD: "Ability to take extreme ownership over your work" — matches Centene's TDD/testing discipline |
| Reordered bullets: PySpark batch pipelines → Databricks ETL → data governance → Agile/Scrum | JD: Agile last since earlier roles carry more technical weight |

---

## Nielsen & Earlier Roles (Nielsen, WellCare, Truist)

| Change | Reason |
|---|---|
| Condensed Nielsen, WellCare, and Truist to 2–3 bullets each | These are pre-Databricks roles from 2014–2018; JD is Databricks/Spark-focused; condensing preserves history without diluting focus |
| Retained SQL tuning and schema design bullets at Nielsen | JD: "Expert-level SQL" — early SQL depth provides supporting evidence |
| Retained SCD Type 2 at WellCare | Shows data modeling discipline in regulated healthcare — adjacent to JD's regulated environments requirement |

---

## What was NOT changed

- All metrics (40%, 35%, 30%) are unchanged — taken verbatim from resume.md
- All company names, dates, and locations are unchanged
- Education section is unchanged
- No new tools, frameworks, or skills were added that do not appear in resume.md
- "Microservices" and "REST API design" were not added to the resume despite appearing in the JD — no supporting evidence in resume.md
