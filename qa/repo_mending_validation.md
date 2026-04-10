# Repo Mending Validation

## Scope of this validation
Reviewed:
- `drafts/final_assignment_report/Final_Assignment_Report_Draft_Mended.md`
- `qa/repo_mending_change_log.md`
- `qa/repo_mending_unresolved_issues.md`
- `qa/scope_logic_note.md`
- `qa/consistency_risks.md`
- `qa/chapter_traceability_map.md`

## 1) Numerical cost-benefit overclaim removal
**Assessment: Mostly adequate (pass with minor cleanup).**

What is now correct:
- Numerical CBA framing is replaced with comparative feasibility language.
- Cost categories are clearly marked as indicative and non-budgetary.
- The report avoids specific monetary values.

Minor residual issue to clean:
- Priority tier language can still be read as stronger-than-evidence ranking finality if not repeatedly tagged as provisional.

**Exact fix:**
- In Section 8.2 table heading, append “(provisional pending Carbon Inventory integration)”.
- Add one sentence after the Section 8.2 table: “These tiers are strategic sequencing guidance for the current evidence cycle and are subject to update after Carbon Inventory integration.”

## 2) Tenure treatment realism (governance/implementation context)
**Assessment: Adequate (pass).**

What is now correct:
- Tenure is framed as governance/access context.
- The report explicitly avoids parcel-level ownership mapping claims.
- Site-level treatment links tenure/governance to implementation implications (enforcement, restoration, benefit-sharing, monitoring continuity).

No major corrective rewrite needed.

## 3) Final report structure fit to ToR-aligned, evidence-based approach
**Assessment: Largely aligned (pass with two targeted improvements).**

What is now correct:
- Required late-stage strategic chapters are present.
- Completed vs in-progress vs pending evidence boundaries are visible.
- Carbon placeholders are retained.

Targeted gaps vs QA risk notes:
1. **Scope authority sentence missing in mended draft.**
   - `qa/consistency_risks.md` recommends a standard statement that ToR + inception + synthesized evidence govern scope, while MRV materials provide implementation detail.
2. **Inception extraction evidence-gap sentence not explicit in mended draft.**
   - `qa/consistency_risks.md` recommends a direct provisionality note.

**Exact fixes:**
- Add a short paragraph in Section 1 (or a subsection “Scope authority and evidence boundary”) stating:
  - “Scope authority remains the ToR, inception process, and synthesized baseline evidence; MRV and related technical materials are implementation-detail inputs and do not redefine scope.”
  - “Inception PDF extraction remains partially constrained in this repository view; refinement details are treated as provisional until direct citation closure.”

## 4) Keta pilot logic correctness
**Assessment: Correctly presented (pass).**

What is now correct:
- Keta is consistently described as pilot implementation context.
- The pilot is repeatedly anchored within a national MRV framework.
- The draft avoids presenting Keta as national substitution.

Minor cleanup for consistency risk #7:
- Ensure every occurrence of “Keta pilot” includes nearby wording “within the national MRV framework” (already mostly done; perform one final line-by-line check).

## 5) Remaining old framing requiring final cleanup pass
**Assessment: A short final cleanup pass is still recommended.**

Remaining items:
1. **Terminology normalization:**
   - “Songor/Ada” and “Songor Ramsar Site (Ada landscape references included)” may still confuse reviewers.
   - Apply one canonical label table or one-line note in Section 3.
2. **Salt marsh visibility:**
   - The mended draft remains mangrove-dominant; add an explicit gap note on tidal salt marsh evidence status to match ToR risk controls.
3. **Priority certainty softening:**
   - Add provisional qualifier to priority ranking section (see item 1 above).

**Exact fixes:**
- Add “Site Name Normalization Note” under Section 3 using canonical labels from `qa/consistency_risks.md`.
- Add one sentence in Sections 4 or 12: “Tidal salt marsh evidence remains under-documented in current extracted materials and is flagged for targeted integration.”
- Add the provisional qualifier sentence in Section 8.2.

## Validation conclusion
The repo mending is directionally correct and substantially aligned with the agreed strategy. A narrow final cleanup pass is still needed for: (i) explicit scope-authority wording, (ii) explicit inception extraction caveat, (iii) terminology normalization, (iv) salt marsh gap visibility, and (v) provisional wording on priority tiers.
