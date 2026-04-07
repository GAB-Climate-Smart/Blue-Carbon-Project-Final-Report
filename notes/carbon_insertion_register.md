---
title: Carbon Inventory Insertion Register
status: ACTIVE — open until Carbon Inventory Report is delivered
opened: 2026-04-07
---

# Carbon Insertion Register

This register tracks every paragraph in the Final Report that depends on the Carbon Inventory Report (still pending from the carbon team, expected within two weeks of 2026-04-07). When the Carbon Inventory Report is delivered, the carbon team or the editor should `grep -rn "CARBON_PENDING:start" final_report/` to find every insertion point. Each block is uniquely tagged so insertions can be tracked and verified one by one.

## How the placeholders work

```markdown
<!-- CARBON_PENDING:start id=CB-XX.X chapter=CHAPTER_NUMBER section=SECTION_NUMBER -->
**[Carbon Inventory pending]** Brief description of what content goes here, written so a non-carbon reviewer understands the gap.
<!-- CARBON_PENDING:end -->
```

## Insertion register

| ID | Chapter | Section | What goes here | Source field needed |
|---|---|---|---|---|
| CB-ES.1 | Executive Summary | Headline numbers | Total ecosystem carbon stock for Keta, Songor, Muni-Pomadze, Ada in tCO2e and per-hectare density | Carbon Inventory §7 |
| CB-04.5 | Ch 4 Methodology | Carbon inventory methods box | One-paragraph summary of the IPCC Tier 2 approach used | Carbon Inventory §3 |
| CB-08.1 | Ch 8 Carbon Stocks | Whole chapter | Complete content drops in here | Carbon Inventory §1 to §10 |
| CB-12.3.4 | Ch 12 Synthesis | Carbon-weighted priority overlay | Per-site carbon density values used to weight the priority matrix | Carbon Inventory §7 |
| CB-12.5 | Ch 12 CBA | Carbon revenue scenarios in the cost-benefit analysis | Per-hectare carbon stock and projected sequestration rate | Carbon Inventory §7, §8 |
| CB-13.4 | Ch 13 Spatial Plan | Carbon priority column in the master spatial intervention table | Per-cluster carbon classification | Carbon Inventory §7, §8 |
| CB-14.2 | Ch 14 Recommendations | Carbon market readiness recommendations | VCS / VM0033 readiness summary | Carbon Inventory §10 |

## Carbon Inventory drop-in template

A drop-in `.md` template for the Carbon Inventory team to fill is available at `source_reports/carbon_inventory_structure_template.md`. Once that template is completed by the carbon team, the editor pulls each section into the corresponding CB-XX block above and removes the placeholder tags.
