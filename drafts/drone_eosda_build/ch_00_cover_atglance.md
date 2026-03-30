# Chapter 0: Cover Page and At a Glance
## Ghana Blue Carbon Assessment — Drone Survey and EOSDA Continuous Monitoring Report

**Build status:** Chapter 0 — Cover + At a Glance
**Chapter-by-chapter build:** Drone Survey & EOSDA Continuous Monitoring Report
**Primary source files used:**
- `drafts/08_drone_survey_and_continuous_monitoring.md`
- `evidence/drone_monitoring.md`
- `drafts/STANDALONE_Drone_Survey_EOSDA_Report.md`
- `STANDALONE_REPORT_STRUCTURES.md` (Report 2 section)
- `source_reports/governance_institutions_and_crema_readiness_report.md` (lines 1–120, FPIC and CREMA definitions)

**Drafting notes:** The file `drafts/mrv_standalone/standalone_drone_monitoring_report.md` referenced in the task specification was not present in the repository; `drafts/08_drone_survey_and_continuous_monitoring.md` was used as the primary drone facts source in its place. FPIC status is marked "Pending confirmation" across all AoIs, consistent with the current readiness-stage evidence in the repository.

---

---

# SECTION A — COVER PAGE

---

## Ghana Blue Carbon Assessment

### Drone Survey and EOSDA Continuous Monitoring Report: Keta Lagoon Complex Ramsar Site

**High-Resolution Aerial Survey, Community-Consented AoI Delineation, and Sentinel-2 Continuous Monitoring**

---

> **\[LOGO PLACEHOLDER — GAB Climate Smart Investment Ltd\]**

---

| Field | Detail |
|---|---|
| **Project Reference** | WACA ResIP 2 — World Bank Project P175525 |
| **Prepared for** | Ministry of Lands and Natural Resources (MLNR), Ghana; Ministry of Environment, Science, Technology and Innovation (MESTI) |
| **Prepared by** | GAB Climate Smart Investment Ltd |
| **Survey Period** | 2025–2026 |
| **Report Date** | 2026 |
| **Version** | V2.0 — Standalone Management Report |
| **Ramsar Sites Covered** | Keta Lagoon Complex Ramsar Site |
| **Classification** | Project Deliverable — Restricted Circulation |

---

**Report Type:** This is a standalone management report prepared as part of the four-report Ghana Blue Carbon Assessment package delivered under WACA ResIP 2. It covers the drone-survey and satellite continuous-monitoring workstream for the Keta Lagoon Complex, including delineation of four Areas of Interest (AoIs) totalling 1,467 Ha, drone survey methodology, EOSDA Sentinel-2 monitoring configuration, and the current readiness and implementation status of the spatial monitoring system.

This report is one of four standalone technical references. Each claim in the Blue Carbon Final Report traces to one of the four standalone documents in this package.

---

---

# SECTION B — AT A GLANCE

---

## B.1 Key Statistics

| Indicator | Value |
|---|---|
| **Areas of Interest (AoIs)** | 4 |
| **Total monitored area** | 1,467 Ha |
| **Ground monitoring stations — Keta Lagoon** | 57 |
| **Satellite revisit frequency (Sentinel-2)** | Every 3–5 days |
| **NDMI change alert threshold** | 15% |
| **Orthomosaic spatial resolution (GSD)** | 5–10 cm |
| **Ground Control Points (GCPs) per AoI — minimum** | 5 |
| **Ramsar sites covered** | Keta Lagoon Complex Ramsar Site |
| **FPIC\* process status** | Pending confirmation across all AoIs |
| **Report version** | V2.0 — Standalone Management Report |

\*FPIC = Free, Prior, and Informed Consent. See FPIC Status Dashboard (Section B.3) and the Governance, Institutions and CREMA Readiness Report (August 2025) for full definitions and process context.

---

## B.2 Four AoI Summary

The drone survey and EOSDA continuous monitoring workstream covers four Areas of Interest within the Keta Lagoon Complex, spanning three spatial clusters and a combined area of 1,467 Ha. The table below summarises each AoI.

| AoI Name | Cluster | Area (Ha) | Ecological Type | Adjacent Communities | FPIC Status | Survey Status |
|---|---|---|---|---|---|---|
| Aborlove Nolopi | Eastern Cluster | 52 Ha | Mixed Degraded and Intact Mangrove | Aborlove, Norlopi | Pending confirmation | Boundary file available; drone survey pending orthomosaic delivery |
| Agatsivi-Agortoe | Central Cluster | 762 Ha | Contiguous and Fragmented Mangrove | Agatsivi, Agortoe, Agbastivi | Pending confirmation | Boundary file available; drone survey pending orthomosaic delivery |
| Salo-Agortoe Stretch | Central Cluster | 525 Ha | Creek System — Near-Community | Salo community | Pending confirmation | Boundary file available; Permanent Sample Plot 1 delineated (NDMI 03 Mar 2026) |
| Anyanui Combine | Western Cluster | 128 Ha | Restoration Potential Zone | Anyanui, Tunu, Fuveme | Pending confirmation | Boundary file available; drone survey pending orthomosaic delivery |
| **TOTAL** | | **1,467 Ha** | | | | |

**Notes on AoI status:** Named boundary files for restoration, protection, and sample-plot contexts are present in the project repository (see `source_reports/` — GeoJSON and KML datasets). These files confirm that monitoring units are spatially defined. They do not by themselves confirm orthomosaic completion, EOSDA upload, or full community consent documentation. FPIC confirmation is a prerequisite for each AoI before operational monitoring is considered fully authorised.

---

## B.3 FPIC Status Dashboard

Free, Prior, and Informed Consent (FPIC) is a foundational requirement for community-consented AoI delineation and drone survey operations in all four clusters. The table below presents the current status of the community engagement and consent process as of the reporting date. This dashboard addresses a gap in the previous draft of this report, which did not formally track consent-process status.

FPIC is defined here in accordance with the World Bank Environmental and Social Standard 7 (ESS7 — Indigenous Peoples/Sub-Saharan African Historically Underserved Traditional Local Communities) and the governance framework established in the Governance, Institutions and CREMA Readiness Report (August 2025). Community Change Agents (CCAs) and Community Resource Management Area (CREMA) structures provide the institutional vehicle for sustained consent and data-access governance at each AoI.

| Activity | Status | Notes |
|---|---|---|
| Traditional authority engagement (chiefs and queen mothers) | **In Progress** | Chiefs and queen mothers at all four AoI clusters have been identified as primary customary governance actors. Engagement is ongoing; no formal written consent from traditional authorities is yet archived in the project repository. |
| Community information meetings | **In Progress** | Field assessments were conducted across Keta Lagoon communities during December 2025. Community Change Agent (CCA) training was completed at this stage. Formal meeting records and attendance registers are pending archiving. |
| FPIC documentation (signed consent forms) | **Pending** | Signed FPIC documentation has not yet been added to the project repository. FPIC confirmation is a prerequisite for each AoI before the drone survey is considered community-authorised. |
| CCA deployment at AoIs | **In Progress** | CCAs were trained in December 2025 and are assigned to monitoring stations across the 57-station Keta ground network. CCA deployment to specific AoI boundary zones is ongoing. |
| Data access agreement with communities | **Pending** | Draft data access agreements covering community rights to drone-derived spatial products and EOSDA monitoring outputs have not yet been finalised or signed. |
| Grievance Redress Mechanism (GRM) in place | **Pending** | A GRM aligned with WACA ResIP 2 Environmental and Social Framework requirements has been designed at the programme level. Site-level GRM activation and community awareness-raising are pending for each AoI cluster. |

**Action required:** FPIC documentation, data access agreements, and GRM activation should be completed and archived before drone survey results are presented to communities or used in any public carbon-credit or finance application. The Governance, Institutions and CREMA Readiness Report (August 2025) provides the framework and institutional map for completing these steps by cluster.

---

## B.4 Technical Status

The table below tracks the current status of key spatial data products and platform elements associated with the drone survey and EOSDA continuous monitoring workstream.

| Technical Element | Status | Detail |
|---|---|---|
| AoI boundary files — Keta Lagoon (keta_lagoon.tif, keta_lagoon_boundary.geojson, keta_lagoon_ramsar_boundary.geojson) | **Complete** | Lagoon and Ramsar boundary layers are present in `source_reports/`. |
| Named AoI GeoJSON boundary files (Aborlove, Salo, Dzita, Avu restoration/protection/PSP polygons) | **Complete** | Seven named boundary datasets are confirmed in `source_reports/`, with date signals from Feb–Mar 2026. |
| Orthomosaic outputs (5–10 cm GSD) | **Pending insertion** | Not yet packaged as report-ready evidence. Required before operational drone survey claims can be made. |
| EOSDA account and AoI boundary upload | **In Progress** | Account setup and boundary upload to EOSDA Crop Monitoring workspace are described as a prepared next step. Upload confirmation and platform screenshots are not yet in the repository. |
| NDMI/NDVI alert system — Sentinel-2 configuration | **Configured** | NDMI alert threshold set at 15%; Sentinel-2 scan cycle of 3–5 days is the monitoring design standard. Platform-level configuration evidence (screenshots or export) is pending. |
| CCA ground verification network — Keta | **Established** | 57 ground monitoring stations at Keta Lagoon are confirmed in the monitoring plan. CCAs trained December 2025. Quarterly field monitoring schedule is in the design-ready stage. |
| Mission logs, flight specifications, and sensor metadata | **Pending** | No drone mission logs or sensor metadata (MicaSense/P4M, RTK specifications) are yet archived in the project repository. |

**Placeholder notice:** Orthomosaic collages, acquisition-date coverage maps, condition-mapping image panels, and EOSDA platform screenshots are required before this report transitions from readiness-status to proof-of-operation status. These are tracked as outstanding deliverables in the project placeholder register.

---

## B.5 Relationship to the Blue Carbon Assessment Architecture

The Drone Survey and EOSDA Continuous Monitoring Report is one of four standalone technical references that together form the Ghana Blue Carbon Assessment package. Each report answers a distinct question in the evidence chain and feeds into MRV reporting and carbon verification.

```
Wetland Ecosystem Health Report
  → What ecological condition are the wetlands in?
  → Provides health baseline for Keta and Ada; links water quality and soil chemistry to carbon stock vulnerability.

Carbon Inventory and Stock Assessment Report
  → What carbon stocks exist, and at what rate are they at risk?
  → Provides biomass, soil organic carbon, and additionality data for Keta, Songor, Muni-Pomadze, and Ada.

Drone Survey and EOSDA Continuous Monitoring Report  ← THIS REPORT
  → How are priority sites spatially defined and continuously tracked?
  → Provides AoI boundaries, drone methodology, Sentinel-2 monitoring design, FPIC and CCA integration,
     and the spatial evidence layer that anchors field stations and repeat observations.

National Blue Carbon MRV Framework Report
  → How is all of the above monitored, reported, and verified nationally?
  → Integrates all four workstreams into a four-tier national MRV architecture aligned with
     Ghana's NDCs, WACA ResIP 2, and Verra/Gold Standard verification pathways.
```

**Feeds into MRV reporting:** The named AoI boundary files, ground station network, and EOSDA satellite monitoring protocol developed in this report supply the spatial specificity and recurring observation data that the National MRV Framework requires for site-level monitoring tiers. NDMI/NDVI alerts from the Sentinel-2 system are designed to trigger field verification by CCAs and escalate to district and national reporting tiers when thresholds are exceeded.

**Feeds into carbon verification:** Spatially defined and community-consented AoI boundaries, combined with orthomosaic condition mapping and permanent sample plot delineation (Salo PSP-1 and equivalents), provide the spatial audit trail required by independent carbon verifiers operating under Verra VM0033 or equivalent methodology. No carbon verification claim should be advanced until orthomosaics, FPIC documentation, and EOSDA upload confirmation are complete.

**Cross-reference structure:**

| This report provides | Used by |
|---|---|
| AoI boundary files and spatial definitions | National MRV Framework (site-level monitoring tier); Carbon Inventory (plot and stratification anchor) |
| 57-station Keta ground monitoring network | National MRV Framework (field verification layer); Ecosystem Health Report (monitoring integration section) |
| NDMI/NDVI alert parameters | National MRV Framework (environmental pressure surveillance); Carbon Inventory (additionality and leakage monitoring) |
| FPIC status and community consent record | All four reports (governance and safeguard prerequisite); carbon market project documentation |
| Orthomosaics and condition mapping \[pending\] | Carbon Inventory (stratum delineation); Ecosystem Health (spatial health condition mapping) |

---

*End of Chapter 0 — Cover Page and At a Glance*

*Next chapter: Chapter 1 — Executive Summary*

---

**Build log:**
- Source file `drafts/mrv_standalone/standalone_drone_monitoring_report.md` was not found in the repository. `drafts/08_drone_survey_and_continuous_monitoring.md` was used as the primary drone facts source.
- FPIC acronym definitions sourced from `source_reports/governance_institutions_and_crema_readiness_report.md` (List of Acronyms, lines 41–88).
- All AoI data, key statistics, and technical status items are drawn from the task specification and confirmed against repository evidence (`evidence/drone_monitoring.md`, `drafts/STANDALONE_Drone_Survey_EOSDA_Report.md`, `STANDALONE_REPORT_STRUCTURES.md`).
- FPIC Status Dashboard is a new addition not present in the prior standalone drone report.
