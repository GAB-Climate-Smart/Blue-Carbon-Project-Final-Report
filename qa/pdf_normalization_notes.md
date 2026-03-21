# PDF Normalization Notes

## Scope
Normalized Markdown extraction completed for:
- `source_reports/draft_inception_report_rev2.pdf`
- `source_reports/ecosystem_report_keta_ada_final_edits_ef_17032026.pdf`

Outputs:
- `normalized/inception_report.md`
- `normalized/ecosystem_health_report_draft.md`

## Extraction history

### Pass 1 — Codex (automated OCR, 21 Mar 2026) — SUPERSEDED
- Output was severely degraded: character spacing artifacts throughout (e.g. `"MI NI STRY OF ENV I RON MENT"`), full document duplication, tables flattened into unreadable prose.
- Files were marked as pre-processing artifacts, not citation-grade.

### Pass 2 — PyMuPDF block extraction (21 Mar 2026) — CURRENT
- Re-extracted using PyMuPDF (`fitz`) with sorted block layout mode.
- Both files are now clean, readable, properly paginated, and deduplicated.
- Results:
  - `ecosystem_health_report_draft.md`: 30 pages, ~51,400 chars
  - `inception_report.md`: 70 pages, ~102,900 chars

## Current extraction quality

**Ecosystem Health Report** (`ecosystem_health_report_draft.md`)
- Full ToC, section headings, results sections readable and correctly structured.
- Key data extracted: pH ranges (6.5–7.5 at Keta), temperature increase (3.2–6.1°C), 140 soil samples at Keta, 28 at Songor/Ada, 57 water quality stations at Keta, 23 at Songor/Ada.
- Figure and table references intact and cross-referenceable.
- Known limitation: embedded chart/figure image data not extractable (figures referenced by caption only).

**Inception Report** (`inception_report.md`)
- Cover letter, executive summary, project charter, methods, work breakdown structure, schedule, and stakeholder sections readable.
- 70 pages paginated with `<!-- Page N -->` markers for cross-referencing to original PDF.
- Known limitation: some complex tables (Gantt chart, WBS matrix) may have column alignment loss.

## Usage guidance
- Files are now **suitable as primary working sources** for a writing agent.
- Page markers (`<!-- Page N -->`) allow cross-referencing to original PDFs for citation-critical values.
- Embedded figure content (charts, maps) cannot be extracted from text; reference by caption label and verify visually in original PDF.
- For final publication, spot-check quoted numeric values against original PDFs.

## Pending QA actions
- [ ] Build section index for `inception_report.md` keyed to original PDF page numbers.
- [ ] Verify Gantt/WBS table reconstruction in `inception_report.md` (complex table columns may be misaligned).
- [ ] Confirm figure captions in ecosystem health report match original PDF figure numbers.
