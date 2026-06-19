---
name: tailor-resume
description: Tailor resume.md for a specific job—fit report, honest tailored resume, change summary, PR-ready outputs.
---

# Tailor resume for one job

## Source of truth

- Read `resume.md` before editing anything. It is the ONLY source of facts.
- Every line in `tailored-resume.md` must trace to something in `resume.md`. Rephrasing, reordering, and re-emphasizing are allowed. Inventing skills, tools, years, metrics, or domains is not.
- JD requirements not supported by `resume.md` go in fit report **Do not add** only—never into `tailored-resume.md`.

## Core principle: maximize *fair* match, not the number

The goal is to lose ZERO points to presentation while losing zero credibility to fabrication. Surface every real match; never manufacture one. A defensible 78% beats an unprovable 90% that collapses in a screen.

## Optimization rules (apply during Tailor step)

1. **Vocabulary mirroring.** When `resume.md` supports a skill the JD names with different words, adopt the JD's exact term. Examples: resume "Spark" + JD "Hive" → use "Hive" ONLY if resume shows Hive/HiveQL work; resume "data pipelines" + JD "data products" → use "data products" if the work fits. Never mirror a term the resume can't back.

2. **Surface buried matches.** If a JD-critical skill exists in `resume.md` but sits in an old role or a deep bullet, lift it into the Summary and the most-recent relevant role. Same fact, better placement.

3. **Lead with JD-critical bullets.** Within each role, reorder so bullets matching the JD's top requirements appear first.

4. **Quantify against JD scale language.** If the JD emphasizes scale ("petabyte," "real-time," "X+ years") and `resume.md` contains supporting numbers, state them explicitly in the matching bullet. Do not invent numbers.

5. **Honest gap mitigation.** For each real gap, the fit report must state the gap AND the strongest *truthful* adjacent strength (e.g. "No Scala; 8 yrs PySpark/Spark — transferable"). Mitigations live in the fit report, never as fake skills in the resume.

## Workflow

1. **Ingest** — Read the per-run prompt (company, role, URL, JD, output paths). Load `references/jd-extraction-taxonomy.md` and classify JD requirements into must-have vs. nice-to-have.
2. **Fit report** — Load `references/fit-report.md`. Score honestly against must-haves first. Pick the fit tier and include the required `**Verdict:**` line. Write `jobs/<company-slug>/<role-slug>/fit-report.md` with **Overall fit**, **Strong matches**, **Gaps** (each with a truthful mitigation), and **Do not add**.
3. **Tailor** — Load `references/keyword-alignment.md` and `references/markdown-resume-structure.md`. Apply the five Optimization rules above. Write `tailored-resume.md` using facts from `resume.md` only.
4. **Change summary** — Load `references/change-summary.md`. Document every edit AND note which JD requirement each change targets, so edits are auditable.
5. **Quality + honesty gate** — Skim `references/anti-patterns.md` and `references/agent-governance.md`. Before finishing, re-scan `tailored-resume.md`: for any claim not traceable to `resume.md`, remove it and move it to **Do not add**. Optional: note plaintext test steps from `references/export-and-plaintext-test.md`.

## Output paths

Per-run prompt specifies:

- `jobs/<company-slug>/<role-slug>/fit-report.md`
- `jobs/<company-slug>/<role-slug>/tailored-resume.md`
- `jobs/<company-slug>/<role-slug>/change-summary.md`

Slug rules: lowercase, hyphenated; strip legal suffixes (Inc, LLC, Ltd) from company names.

## PR

Title: `feat: tailor resume for <role> at <company>`

Commit all three files on the agent branch. Do not modify `resume.md` on `main`.
