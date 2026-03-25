# AUTHORING_GUIDE.md

**Project:** Assessment of Blue Carbon Ecosystem Potentials of Ghana
**Document type:** Authoring standard and progress tracker
**Applies to:** MRV Standalone Report (client-facing Word document)
**Status:** Active — maintained across sessions
**Relation to other instruction files:** This guide is ADDITIVE. It does not replace `AGENTS.md`, `project_scope_logic.md`, or `AI_BLUEPRINT.md`. It adds an authoring-specific layer for the MRV Standalone Report.

---

## 1. What This Guide Is For

This guide exists because producing a technically accurate report is not the same as producing a well-authored one. The source reports in `source_reports/` are rich with specific data, named communities, causal analysis, and site-level differentiation. That depth must make it into the authored text. Previous attempts produced prose that was structurally correct but too generic — restating concepts rather than grounding claims in the actual evidence from the baseline package.

This guide gives every agent — and every new session — everything needed to:
- understand what is being authored and why;
- write to the style standard established in the source reports;
- pick up exactly where the previous session ended;
- maintain coherence across chapters authored in separate sessions; and
- know what still needs to be done.

---

## 2. What We Are Authoring

**The MRV Standalone Report** is a client-facing document delivered to MESTI and MLNR as a formal government output of the WACA Blue Carbon Assessment (World Bank WACA ResIP 2, P175625). It is:

- written in the author's voice — professional, analytical, evidence-grounded;
- free of internal notes, meta-commentary, or scope negotiation language;
- designed to function as a standalone operational reference for government, development partners, and carbon market reviewers;
- one deliverable within a wider baseline package (see `blue_carbon_final_report_blueprint.md` for how it fits into the Final Report).

It is **not**:
- a draft for internal review;
- a pointing document ("see evidence pack X for details");
- a generic framework description that could apply to any country;
- a replacement for the Final Report (which has its own chapter structure in `blue_carbon_final_report_blueprint.md`).

The MRV Standalone Report chapter structure is:

| # | Chapter Title |
|---|---|
| ES | Executive Summary |
| 1 | Introduction |
| 2 | Strategic Context and National Purpose |
| 3 | National MRV Architecture |
| 4 | Ecological and Carbon Integrity Layer |
| 5 | Environmental Pressure Surveillance |
| 6 | Governance and Safeguard Assurance |
| 7 | Wetland Ecosystem Monitoring (Keta and Ada) |
| 8 | Digital Platform and Data Architecture |
| 9 | Carbon Accounting Protocol |
| 10 | Reporting Framework |
| 11 | Keta Pilot Implementation |
| 12 | Implementation Maturity Assessment |
| A | Annexes |

---

## 3. Authoring Approach — Chapter by Chapter

**Each chapter is authored as its own standalone file.** This is deliberate: it gives the authoring agent an undivided context window to read all relevant source material deeply and write with the density and specificity the report requires.

**File location:** `drafts/mrv_standalone/`
**File naming:** `ch_ES_executive_summary.md`, `ch_01_introduction.md`, `ch_02_strategic_context.md`, etc.

**The authoring sequence for each chapter:**
1. Identify which source reports are relevant to the chapter (see Section 7 below).
2. Read all relevant source files in full — do not skim.
3. Absorb the style, then write the chapter as authored prose.
4. No chapter is complete until it passes the quality test in Section 5.

**Once all chapters are authored individually, the user will assemble them into a single document. The agent will then receive the assembled document and conduct a final coherence and QA review against the rules in this guide and in `AGENTS.md`.**

---

## 4. Style Standard

The benchmark for writing style is the source reports in `source_reports/`. Read at minimum the executive summary and Section 4 of `environmental_pressures_and_community_dependency_report.md` and Sections 1–2 of `geo_social_mangrove_extent_baseline_report.md` before writing any chapter. The writing standard these reports set is:

### 4.1 Evidence-led paragraphs
Every paragraph opens with a claim or analytical finding, then immediately grounds it in specific evidence — real numbers, named sites, named communities, dated events. Do not state a general principle and then move on without the evidence.

**Wrong:** "Mangrove degradation is a significant challenge across all three sites."
**Right:** "The 2024 geospatial assessment found only 465.76 hectares of mangroves remaining at the Songor Ramsar Site — 2% of the national total — distributed as small, fragmented patches across a landscape increasingly dominated by salt pans driven by industrial and artisanal salt mining at Elavanyo, Obane, and surrounding areas."

### 4.2 Causal and analytical prose — not just description
The source reports do not only say what was found. They explain WHY it happened and WHAT IT MEANS for project design and management. Every major finding must carry an analytical implication.

**Wrong:** "The Keta Lagoon has high livelihood dependency."
**Right:** "This creates a social-ecological trap in which the practices required to maintain livelihoods progressively undermine the ecological foundations that make those livelihoods possible."

### 4.3 Site-specific differentiation — always
Keta, Songor, and Muni-Pomadze are never generic or interchangeable. Each has a distinct character, scale, and strategic implication. Name them explicitly, use their actual numbers, and give each site its own analytical framing. The source reports use site-specific metaphors: Keta = "death by a thousand cuts," Songor = "landscape of conflict and extraction," Muni-Pomadze = a restoration landscape, not a conservation one.

### 4.4 Named communities and examples
Always use specific community names drawn from the source reports. Do not write "communities in the Keta area" when you can write "communities including Agbatsivi, Galotse, Bomigo, Salo, and Dzita." Named examples make the report credible, readable, and distinctly Ghanaian.

Key community names approved for use:
- **Keta:** Dzita, Salo, Agbatsivi, Bomigo, Galotse, Sota, Galo
- **Songor:** Pute, Elavanyo, Obane, Totope, Azizanya
- **Muni-Pomadze:** Sankor

### 4.5 Active voice and precise nouns
The source reports write in active voice with precise, concrete nouns. Avoid passive constructions and vague references.

**Wrong:** "Carbon data will be used by relevant institutions."
**Right:** "MLNR and MEST will use annual carbon stock updates to report against Ghana's NDC commitments and to assess progress toward national restoration targets."

### 4.6 Tables and structured elements support, never replace, prose
Tables may appear in the text to organise comparative data, but the analytical argument must always be made in the prose first. A table without surrounding analytical narrative is insufficient.

### 4.7 No internal process language in the final text
The authored text is addressed to the client and to future users of the report. Do not write: "As noted in the evidence pack...", "Pending evidence...", "Per the scope logic file...", or any language that reveals internal authoring process. Write as if the author has personally conducted and synthesised the research.

### 4.8 Acronyms
Define every acronym at first use in each chapter. The report will be read as an assembled whole, but chapters must also be independently intelligible. Key definitions to always carry:

- MRV — Monitoring, Reporting, and Verification
- WACA — West Africa Coastal Areas Resilience Investment Project
- CREMA — Community Resource Management Area
- CCA — Community Change Agent
- MESTI — Ministry of Environment, Science, Technology and Innovation
- MLNR — Ministry of Lands and Natural Resources
- IPCC — Intergovernmental Panel on Climate Change
- NDC — Nationally Determined Contribution
- PSP — Permanent Sample Plot
- GEE — Google Earth Engine
- FPIC — Free, Prior, and Informed Consent

---

## 5. Quality Test — Before Marking a Chapter Complete

Before marking any chapter as done, test it against these questions:

1. **Specificity:** Does every factual claim have a real number, a named site, a named community, or a dated event behind it? Could you replace any sentence with something more specific?
2. **Causality:** Does the chapter explain WHY things are the way they are, not just WHAT they are?
3. **Site differentiation:** If Keta, Songor, and Muni-Pomadze are all relevant to this chapter, are they treated as distinct, with their own numbers and character?
4. **Voice:** Does the text read as authored client-facing prose, or does it sound like an internal summary of an evidence pack?
5. **No generic statements:** Read every paragraph and ask: could this sentence appear in a report about any coastal country's mangroves? If yes, make it specific to Ghana, to this landscape, to these findings.
6. **Coherence markers:** Are the key cross-chapter facts and terms consistent with Section 6 below?

---

## 6. Coherence Threads — Facts and Framings That Must Be Consistent Across All Chapters

The following facts and framings are established in the early chapters and must not be contradicted or restated differently in later chapters. Any agent continuing this work must read these before writing.

### Approved numbers (use exactly as stated)
- Total coastal mangrove extent: **30,025 hectares** (2.81% of coastal landscape)
- Total coastal landscape assessed: **1,068,361.48 hectares**
- Number of districts: **35**
- Coastline length: **550 km**
- Keta Lagoon mangrove extent: **20,717.95 hectares** (approximately 69% of national total)
- Songor mangrove extent: **465.76 hectares** (2% of national total)
- Muni-Pomadze mangrove extent: described as **ecologically insignificant**
- Historical mangrove extent range: **7,240 ha (2013) to 18,100 ha (1980)**
- Ground-truth reference points: **319**
- Communities profiled: **37**
- Household livelihood dependency: **>70%** (mangrove-linked activities)
- Akosombo Dam sediment trapping: **>90%** of Volta River sediment load
- Akosombo Dam construction: **1964**
- Historical deforestation rate at Keta: **2.15% per year**
- Carbon storage comparison: blue carbon ecosystems store up to **10x more carbon per hectare** than terrestrial forests
- WACA ResIP 2 World Bank approval: **December 2022**
- WACA ResIP 2 project number: **P175625**
- Keta monitoring stations: **57**
- Ada monitoring stations: **23**
- MRV biomass re-measurement cycle: every **3–5 years**
- CREMA female leadership minimum: **40%**
- Communities with informal grievance systems: **>80%**
- Anloga female-headed households: **46.2%** (national average 35.3%)
- Volta Region age dependency ratio: **73.1**
- Youth share in project communities (field estimate): **>50%**
- Imaging resolution: **Sentinel-2, 10–20 m**

### Approved site framings (use these characterisations consistently)
- **Keta Lagoon Complex:** Ghana's principal blue carbon asset; 69% of national mangrove total; conservation priority, not primarily a restoration site; intense livelihood-driven pressure from fish-smoking fuelwood demand; Akosombo Dam as the landscape-level existential risk; primary MRV pilot site.
- **Songor Ramsar Site:** Severely degraded; landscape of conflict between salt production and traditional ecosystem-dependent livelihoods; CREMA formation emerging but contested; restoration and land-use planning priority.
- **Muni-Pomadze Ramsar Site:** Ecologically insignificant mangrove cover; not a carbon stock conservation site — a restoration and ecosystem re-establishment landscape; high community cohesion at Sankor; CREMA interest strong.

### Approved early action hubs
- **Dzita** — Keta Lagoon Complex
- **Pute** — Songor Ramsar Site
- **Sankor** — Muni-Pomadze Ramsar Site

### Approved institutional hierarchy
1. MESTI (lead ministry, Ghana WACA)
2. MLNR (co-lead and MRV custodian)
3. Forestry Commission / Wildlife Division (technical arm)
4. MMDAs (district level)
5. CREMAs and CCAs (community level)

### Carbon assessment methodology
- Imagery: Harmonised Sentinel-2, 10–20 m resolution
- Classification: Random Forest algorithm on Google Earth Engine (GEE)
- Validation: 319 participatory ground-truth reference points
- Carbon pools: AGB, BGB, deadwood (where relevant), SOC 0–100 cm (IPCC Wetlands Supplement)
- PSP re-measurement cycle: every 3–5 years

### MRV institutional tiers (in order)
1. Community (CREMAs and CCAs)
2. District (MMDAs and Wildlife Division)
3. National Technical (MLNR, MESTI, Forestry Commission)
4. Independent Review (where required for carbon markets)

### MRV functional layers (in order)
- Layer I: Ecological and Carbon Integrity
- Layer II: Environmental Pressure Surveillance
- Layer III: Governance and Safeguard Assurance

### Species names
- Red Mangrove: *Rhizophora racemosa*
- Black Mangrove: *Avicennia germinans*

---

## 7. Chapter Progress Tracker

| Chapter | Title | Status | File | Lead source reports |
|---|---|---|---|---|
| ES | Executive Summary | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_ES_executive_summary.md` | All chapters (synthesised from ch_01–ch_12) |
| 1 | Introduction | ✅ Authored (standalone v2) | `drafts/mrv_standalone/ch_01_introduction.md` | ToR, blueprint, scope logic |
| 2 | Strategic Context and National Purpose | ✅ Authored (standalone v2) | `drafts/mrv_standalone/ch_02_strategic_context.md` | ToR, geo-social baseline, EPCR |
| 3 | National MRV Architecture | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_03_mrv_architecture.md` | `blue_carbon_mrv_report.md`, `governance_institutions_and_crema_readiness_report.md` |
| 4 | Ecological and Carbon Integrity Layer | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_04_ecological_carbon_integrity.md` | `blue_carbon_mrv_report.md`, `soil_and_carbon_data.md`, `monitoring_plan_for_keta_and_ada.md`, `geo_social_mangrove_extent_baseline_report.md` |
| 5 | Environmental Pressure Surveillance | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_05_environmental_pressure_surveillance.md` | `environmental_pressures_and_community_dependency_report.md`, `blue_carbon_mrv_report.md`, `geo_social_mangrove_extent_baseline_report.md` |
| 6 | Governance and Safeguard Assurance | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_06_governance_safeguard_assurance.md` | `governance_institutions_and_crema_readiness_report.md`, `risk_assessment_and_safeguards_report.md`, `gender_and_social_inclusion_report.md` |
| 7 | Wetland Ecosystem Monitoring (Keta and Ada) | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_07_wetland_ecosystem_monitoring.md` | `monitoring_plan_for_keta_and_ada.md`, `ecosystem_report_keta_ada_final_edits_ef_17032026.pdf`, `geo_social_mangrove_extent_baseline_report.md` |
| 8 | Digital Platform and Data Architecture | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_08_digital_platform.md` | `AI_BLUEPRINT.md`, `blue_carbon_mrv_report.md`, `drafts/STANDALONE_Drone_Survey_EOSDA_Report.md` |
| 9 | Carbon Accounting Protocol | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_09_carbon_accounting_protocol.md` | `soil_and_carbon_data.md`, `blue_carbon_mrv_report.md`, ToR, `geo_social_mangrove_extent_baseline_report.md` |
| 10 | Reporting Framework | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_10_reporting_framework.md` | `blue_carbon_mrv_report.md`, ToR |
| 11 | Keta Pilot Implementation | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_11_keta_pilot_implementation.md` | `monitoring_plan_for_keta_and_ada.md`, `geo_social_mangrove_extent_baseline_report.md`, `blue_carbon_mrv_report.md`, `environmental_pressures_and_community_dependency_report.md` |
| 12 | Implementation Maturity Assessment | ✅ Authored (standalone v1) | `drafts/mrv_standalone/ch_12_implementation_maturity.md` | `governance_institutions_and_crema_readiness_report.md`, `blue_carbon_mrv_report.md`, `monitoring_plan_for_keta_and_ada.md`, `AI_BLUEPRINT.md`, `evidence/mrv_system.md` |
| A | Annexes | 🔲 Not started | — | All sources |

**Status legend:**
- ✅ Authored — chapter complete and quality-checked
- 🔄 In progress — actively being written in current session
- 🔲 Not started — awaiting authoring session
- ⚠️ Needs revision — authored but flagged for improvement

> **Note on Chapters 1 and 2:** These were authored in an earlier session using a JavaScript/docx generation approach. They are saved in `STANDALONE_National_MRV_Report_v2.docx` in the repo root AND as standalone `.md` files in `drafts/mrv_standalone/`. The Executive Summary has been re-authored from scratch as a standalone `.md` file synthesising all 12 chapters (March 2026), superseding the earlier v1 in the .docx. For final assembly, use the standalone `.md` files in `drafts/mrv_standalone/`.

---

## 8. Chapter-by-Chapter Authoring Notes

Each entry below tells the next agent what the chapter must achieve, what to read before writing it, and what specific evidence must appear.

### Chapter 3: National MRV Architecture

**What it must achieve:** Show the reader exactly how the MRV system is structured — the four institutional tiers and three functional layers — and explain why each exists, what it does, and how they connect. This is not a schematic description; it is an authored explanation of the logic behind each design decision.

**Read before writing:** `source_reports/blue_carbon_mrv_report.md` (Sections 2 and 3 especially).

**Must include:**
- The four tiers named and described with their actual responsibilities (not just roles)
- The three functional layers with their logic — why they are three layers and not one
- How the layers interact (governance instability as carbon risk signal, etc.)
- The CREMA and CCA system explained within the tier structure
- The district-level validation role of the Wildlife Division
- MLNR and MESTI as joint custodians at national level
- Independent review: when it applies and when it doesn't
- A table summarising the three layers (Layer / Focus / Key outputs)
- Why the system was designed for institutional permanence beyond the WACA project cycle

**Coherence check:** Confirm tier names and functional layer names match Section 6 of this guide before finalising.

---

### Chapter 4: Ecological and Carbon Integrity Layer

**What it must achieve:** Describe precisely how carbon stocks are monitored — what is measured, when, by whom, using which methods — and ground it in the actual PSP network and field protocols established for this project.

**Read before writing:** `blue_carbon_mrv_report.md` (Layer I section), `soil_and_carbon_data.md`, `monitoring_plan_for_keta_and_ada.md`.

**Must include:**
- The four carbon pools: AGB, BGB, deadwood (where relevant), SOC to 100 cm
- IPCC Wetlands Supplement as the methodological reference
- PSP structure and location (Salo PSP as the named example)
- Re-measurement cycle: every 3–5 years
- Mangrove extent monitoring via Sentinel-2 and GEE — annual cadence
- Restoration performance monitoring: survival rates, canopy cover, recruitment
- The 2.15%/yr historical deforestation rate at Keta as the baseline degradation context
- The early action hubs (Dzita, Pute, Sankor) as the initial restoration monitoring sites
- How the ecological layer feeds into carbon accounting (Section 9 reference)

---

### Chapter 5: Environmental Pressure Surveillance

**What it must achieve:** Show how the MRV system detects and responds to the actual drivers of ecosystem degradation that are documented in the baseline — fuelwood harvesting, salt production, coastal erosion, pollution, Akosombo Dam effects. The surveillance indicators must feel grounded in the Ghanaian landscape, not generic.

**Read before writing:** `environmental_pressures_and_community_dependency_report.md` (the most important source for this chapter), `blue_carbon_mrv_report.md` (Layer II section).

**Must include:**
- The five core indicators from the MRV system design
- Site-specific pressure profiles for each Ramsar site:
  - Keta: fuelwood demand from fish smoking, Rhizophora preference, Akosombo sediment starvation, coastal retreat
  - Songor: salt pan expansion, land tenure conflict, Elavanyo/Obane case examples
  - Muni-Pomadze: agricultural encroachment, charcoal production, low mangrove density
- The "death by a thousand cuts" framing for Keta
- The "landscape of conflict and extraction" framing for Songor
- How pressure signals trigger escalation through the institutional tiers
- Leakage risk management: what leakage means in this context, how it is monitored
- The role of communities and CCAs in detecting and reporting pressure signals

---

### Chapter 6: Governance and Safeguard Assurance

**What it must achieve:** Explain how the MRV system ensures that participation is inclusive, benefits are transparent, grievances are heard, and the governance structures are functioning as designed. Ground it in the actual governance gaps documented in the baseline.

**Read before writing:** `governance_institutions_and_crema_readiness_report.md`, `risk_assessment_and_safeguards_report.md`, `gender_and_social_inclusion_report.md`, `blue_carbon_mrv_report.md` (Layer III section).

**Must include:**
- The minimum 40% female representation requirement in CREMA executive leadership
- The >80% informal grievance system finding as the baseline gap this layer is designed to address
- Site-by-site CREMA readiness: high at Muni-Pomadze (Sankor), emerging at Songor (Pute), fragmented at Keta (Dzita)
- FPIC requirements and how they are embedded in the governance monitoring cadence
- Elite capture and exclusion risks — named as high-risk if CREMA formation reproduces current power asymmetries
- Anloga district context: 46.2% female-headed households, high dependency ratio
- GRM (Grievance Redress Mechanism) requirement at each landscape
- Benefit-sharing transparency indicators

---

### Chapter 7: Wetland Ecosystem Monitoring (Keta and Ada)

**What it must achieve:** Describe the physical monitoring network at Keta and Ada in operational detail — the stations, the parameters, the schedule, the field protocols — and explain why this network was designed as it was.

**Read before writing:** `monitoring_plan_for_keta_and_ada.md` (primary source), `ecosystem_report_keta_ada_final_edits_ef_17032026.pdf` (if accessible — check file size before reading).

**Must include:**
- 57 monitoring stations at Keta, 23 at Ada — named explicitly
- Quarterly monitoring schedule
- Water parameters: pH, temperature, conductivity, salinity, TDS, dissolved oxygen, ORP, resistivity
- Soil parameters: nitrate, phosphate, potassium, pH, moisture, humus content, temperature
- How this monitoring network connects to the three MRV functional layers
- The hydrological rationale: why these specific parameters for these specific sites

---

### Chapter 8: Digital Platform and Data Architecture

**What it must achieve:** Describe the web-based platform that aggregates MRV data, enables reporting, and provides institutional oversight — including what has been built and what is planned.

**Read before writing:** `AI_BLUEPRINT.md`, `blue_carbon_mrv_report.md` (platform section).

**Must include:**
- Organisation: GAB Climate Smart Investment Ltd
- Tech stack: Next.js / Supabase / Vercel (as described in AI_BLUEPRINT.md)
- Supabase project reference: eavqytqxeaswfbytguxs
- GitHub: GAB-Climate-Smart/blue-carbon-mrv
- EOSDA hosting for continuous satellite monitoring (reference from `STANDALONE_Drone_Survey_EOSDA_Report.md`)
- Year 0 data archiving protocols
- Roles: who submits data, who reviews, who publishes
- What is live versus what is planned

> **Important:** Do NOT claim the platform is fully operational if the evidence does not confirm this. Follow the AGENTS.md rule: "claims that EOSDA monitoring is already operational without evidence of account setup, area upload, or reporting outputs" is a red flag.

---

### Chapter 9: Carbon Accounting Protocol

**What it must achieve:** Describe the methodology by which carbon stocks are calculated, changes are attributed, and credits are prepared — in enough detail that a carbon market reviewer would accept it as a credible accounting reference.

**Read before writing:** `soil_and_carbon_data.md`, `blue_carbon_mrv_report.md` (carbon protocol section), ToR (`terms_of_reference_revised_mlnr.md`, context of assignment section).

**Must include:**
- Compliance and voluntary market standard alignment: Verra/VCS, Gold Standard, Plan Vivo
- The four carbon pools (AGB, BGB, deadwood, SOC)
- IPCC Wetlands Supplement as the accounting methodology reference
- Baseline carbon stock figures from the 2025 inventory (use approved numbers from `soil_and_carbon_data.md`)
- Additionality: what the baseline scenario is and why project activities are additional
- Permanence and leakage: how these risks are managed within the accounting protocol
- Re-measurement cycle and uncertainty quantification
- How carbon accounting connects to reporting (Chapter 10 reference)

---

### Chapter 10: Reporting Framework

**What it must achieve:** Set out the full reporting cycle — what is reported, when, by whom, in what format, and to which audiences — including national reporting obligations and carbon market reporting requirements.

**Read before writing:** `blue_carbon_mrv_report.md` (reporting section), ToR (deliverables and reporting sections).

**Must include:**
- Annual National Blue Carbon MRV Report as the primary national reporting product
- Quarterly field data reporting cycle
- Five-year comprehensive review cycle
- Audiences: MESTI/MLNR, Forestry Commission, World Bank/WACA, development partners, carbon market verifiers
- NDC reporting linkage
- How the platform (Chapter 8) feeds the reporting cycle

---

### Chapter 11: Keta Pilot Implementation

**What it must achieve:** Show what Keta-specific implementation looks like — what has been done at Keta that is more detailed than at other sites, why Keta was selected as the MRV pilot, and what the pilot experience means for national rollout.

**Read before writing:** `monitoring_plan_for_keta_and_ada.md`, `geo_social_mangrove_extent_baseline_report.md` (Keta sections), `blue_carbon_mrv_report.md` (pilot section).

**Must include:**
- Why Keta: deepest layered baseline, most complete monitoring package, highest national carbon significance
- The 57-station monitoring network as the operational pilot infrastructure
- The Dzita early action hub and its social readiness profile
- PSP locations (Salo as named example)
- CREMA formation status at Keta
- What the pilot has established that can be replicated at Songor and Muni-Pomadze
- The landscape risks (Akosombo Dam, coastal erosion, fuelwood pressure) as the stress-test context for the MRV design

---

### Chapter 12: Implementation Maturity Assessment

**What it must achieve:** Give an honest, evidence-based assessment of where the MRV system currently stands in terms of operational maturity — what is fully in place, what is partially in place, and what remains to be built or resourced.

**Read before writing:** All source reports, particularly `governance_institutions_and_crema_readiness_report.md` and the monitoring plan.

**Must include:**
- A maturity assessment across the four tiers and three layers
- What is operational (monitoring stations, PSPs, geo-social baseline, platform prototype)
- What is partially operational (CREMA readiness is uneven; governance structures emerging)
- What requires further investment (independent review capacity, digital platform full build, Ada/Songor station network expansion)
- The distinction between MRV framework design (complete) and MRV system operationalisation (in progress)

---

## 9. What NOT to Do (Anti-patterns)

These failures are specifically prohibited in the authored text:

| Anti-pattern | Example of what to avoid |
|---|---|
| Generic tropical mangrove prose | "Mangroves play a vital role in coastal ecosystems worldwide." |
| Internal evidence reference | "As shown in the socio-economic evidence pack..." |
| Scope negotiation language | "While this report focuses primarily on MRV design, it is worth noting that..." |
| Uncommitted hedging | "There may be some degree of livelihood dependency in certain communities." |
| Lists instead of prose | Bullet-pointing findings that deserve analytical paragraphs |
| Interchangeable site treatment | Describing Keta, Songor, and Muni-Pomadze as if they have equivalent ecological status |
| Placeholders left without prose | Writing "[PLACEHOLDER]" where source data is actually available in the source reports |
| Over-claiming operational status | Stating that platforms or monitoring systems are fully operational without source evidence |
| Invented numbers | Any number not traceable to an approved source in Section 6 of this guide |
| Missing acronym definitions | Using CREMA, MRV, NDC, etc. without defining at first use |

---

## 10. The Stitching and Final Review Plan

1. **Authoring:** Each chapter is written as its own `.md` file in `drafts/mrv_standalone/`.
2. **Assembly:** The user stitches the individual chapter files into a single document.
3. **Final review:** The agent receives the assembled document and conducts a review pass against:
   - Coherence of numbers across chapters (Section 6 of this guide)
   - Consistency of site framings
   - Acronym definitions
   - No contradictions between chapters
   - Narrative flow across chapter boundaries
   - The quality tests in Section 5 of this guide
4. **Word document production:** Once the assembled `.md` is approved, it is formatted into the final Word document using the `docx` skill.

---

## 11. Session Handover Protocol

When an authoring session ends:

1. Update the **Chapter Progress Tracker** in Section 7 of this file — change status of completed and in-progress chapters.
2. Note in the tracker any **decisions made** that future agents must not reverse (e.g., a site framing, a number interpretation, a structural choice).
3. If a chapter was partially written, note the **last subsection completed** and what comes next.
4. **Commit the chapter file** to `drafts/mrv_standalone/` so it persists across sessions.
5. Do not leave any chapter file in draft state inside the session temporary folder — always copy to the repo folder.

---

*This guide was created in March 2026 following a session review that identified generic authoring as the primary quality gap in the MRV Standalone Report. It is maintained as a living document and updated at the end of each authoring session.*
