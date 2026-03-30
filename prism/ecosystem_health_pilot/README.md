# Prism Ecosystem Health Pilot Package

This folder is a **Prism import-ready scaffold** for piloting the Ecosystem Health standalone report in OpenAI Prism.

## Purpose
- Keep the repository as the source-of-truth for evidence and governance.
- Use Prism for final authoring, formatting, compile checks, and readability improvements.
- Enforce Blue Carbon report constraints inside Prism prompts.

## Source of truth
- Primary source report: `source_reports/STANDALONE_Ecosystem_Health_Report_v2.md`
- Core governance rules: `AGENTS.md`
- Workflow sequence and QA expectations: `workflows/REPORT_EXECUTION_PACK.md`, `qa/QA_CHECKLIST.md`

## Folder contents
- `main.tex` — LaTeX assembly entrypoint for Prism.
- `chapters/` — chapter-level `.tex` files for modular editing.
- `refs/references.bib` — bibliography placeholder.
- `assets/` — figures and tables for report-ready build.
- `prompts/prism_system_prompt.md` — hard constraints for Prism assistant behavior.
- `prompts/prism_tasks.md` — session task templates.
- `governance/evidence_rules.md` — evidence traceability and claim controls.
- `governance/unresolved_gaps.md` — known missing inputs and blockers.

## How to use
1. Populate chapter `.tex` files from the approved markdown source material.
2. Keep unresolved fields marked with bracketed placeholders.
3. Zip this folder and import it into Prism using **Import**.
4. In Prism, paste `prompts/prism_system_prompt.md` as your instruction block before edits.
5. Run authoring and formatting passes; do not add net-new findings.
6. Export Prism project ZIP and commit outputs back into this repo for QA.

## Status convention
Use these tags in draft text:
- `[COMPLETED EVIDENCE]`
- `[PENDING INPUT]`
- `[INTERPRETIVE SYNTHESIS]`
- `[RECOMMENDATION]`
- `[ASSUMPTION]`

## Non-negotiable rule
If evidence is missing, keep a placeholder and identify the missing source; do not invent facts.
