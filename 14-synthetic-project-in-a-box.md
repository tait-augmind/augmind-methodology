# 14 — Synthetic Project in a Box

**Status:** Template complete. All figures are modeled from published benchmarks and a de-identified spend shape. Replace modeled numbers with client data at Stage 03. Nothing here is a live client.

**Client (synthetic):** Northbridge Auctions — Mid-Atlantic regional real estate auction firm; three rainmaker partners; commercial / residential / land books; parent franchise controls the national site.

**Method spine:** Three Frameworks → Delivery Methodology (01–05) → Pricing Methodology. Every deliverable traces to a stage, work item, deliverable code, and gate.

**Process source:** National Auctioneers Association “Streamlined Operations: From Contract to Close” plus published auction-house process guides (Mike Walker 19-step, Alex Cooper 4-phase).

**Documentation standard:** BPMN 2.0 / ISO/IEC 19510:2013 (OMG).

**Advisory overlay:** KPMG data-driven current-state baseline; Deloitte “redesign the workflow, do not automate the task.”

## Benchmarks used (USD)
- LocaliQ / WordStream real estate search ads 2026: CTR 7.61%, CPC $3.22, conversion 3.70%, CPL $102.51.
- Auctioneer industry 2026: visitor-to-registration 8.5%, registration-to-bidder 35%, cost per registered bidder $28–$42, cost per consignment lead $85–$120.
- Top-performing estate houses: marketing 2–3% of expected GMV.
- Referral economics: referred prospects convert ~4× faster; 37% higher retention; 55–70% cheaper than paid.
- Document automation case studies: 40+ hours/month saved; 95–97% first-pass accuracy; 20–40 min → under 2 min per form.

## Lane A — Property Marketing
| Phase | Inputs | Work | Outputs | Gate |
|---|---|---|---|---|
| 01 Discover | Campaign spend file; channel mix; views-to-downloads gap | Current-state; future-state; problem decomposition | D1.1 Current-State Assessment; D1.2 Problem Decomposition; D1.3 Future-State Vision | G1 |
| 02 Design | Benchmarks; channel hypothesis | Business case; operating model; roadmap; SOW; measurement lock | D2.1–D2.3; D1.4 Statement of Work | G2 |
| 03 Implement | Landing pages; ad accounts; CRM | Retargeting; LP tests; channel reallocation; prospecting automation | D3.1 Implemented campaigns; D3.2 Change Control Notes | G3 |
| 04 Validate & Run | Cycle results | Value realization; runbook; retainer | D4.1 Runbook; D4.2 Retainer | G4 |
| 05 Review | Accumulated cycles | Trend; quality review; next-cycle plan | D5.1 Improvement Report; D5.2 Quality sign-off | G5 |

## Lane B — Seller & Referral Relationships
| Phase | Inputs | Work | Outputs | Gate |
|---|---|---|---|---|
| 01 Discover | Partner books; referral sources | Referral map; source segmentation | D1.1 Referral Map; D1.2 Source Segmentation | G1 |
| 02 Design | Referral benchmarks; partner capacity | Referral engine; nurture cadence; measurement lock | D2.1 Referral Engine; D2.2 Nurture Cadence | G2 |
| 03 Implement | CRM; lists; content | Sequences; ask prompts; outreach | D3.1 Live sequences; D3.2 Referral Dashboard | G3 |
| 04 Validate & Run | Conversion data | Value realization; runbook | D4.1; D4.2 | G4 |
| 05 Review | Cycle data | Trend; quality review | D5.1 | G5 |

## Lane C — Paperwork & Data Entry
| Phase | Inputs | Work | Outputs | Gate |
|---|---|---|---|---|
| 01 Discover | Form inventory; time-per-form; error rate | Process map; opportunity sizing | D1.1 Process Map; D1.2 Opportunity Sizing | G1 |
| 02 Design | Templates; data sources | Automation design; TOM; measurement lock | D2.1 Automation Design; D2.2 Operating Model | G2 |
| 03 Implement | Form-fill tool; integrations | Deploy; train; monitor accuracy | D3.1 Automated forms; D3.2 Training records | G3 |
| 04 Validate & Run | Accuracy and time data | Value realization; runbook | D4.1; D4.2 | G4 |
| 05 Review | Cycle data | Trend; quality review | D5.1 | G5 |

Cross-lane traceability: every deliverable code maps to Framework → Stage → Work item → Deliverable → Gate. Change Control Notes apply to any scope move in any lane.
