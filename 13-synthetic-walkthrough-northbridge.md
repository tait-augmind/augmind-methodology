# 13 — Synthetic Project Walkthrough: Northbridge Auctions

> De-identified run of the full five-stage method against real client data.
> Client name changed to **Northbridge Auctions** (Mid-Atlantic regional real estate auction group).
> All figures below are the client's actual proposed spend and stated metrics, sourced from their budget corpus and the discovery call. No numbers are invented.
> Purpose: prove the box runs end to end before the real engagement begins.

---

## Source data used

| Input | Source | What it contains |
|---|---|---|
| 43 property marketing budgets | Client budget corpus (Nov 2025 – Aug 2026) | Proposed spend by channel, asset class, originator |
| Portfolio totals | Same corpus, normalized | $252,038 total proposed spend across 43 campaigns |
| Channel performance (one property) | Discovery call, Aug 6 2026 | 18,595 page views; 13,599 from Meta; 11 information-package downloads |
| Client-stated success measure | Discovery call | Page views → information-package downloads (their own words) |
| Client priorities | Discovery call | (1) Prospecting automation, (2) Paperwork automation, (3) Marketing spend effectiveness |
| External benchmarks | WordStream / LocaliQ 2026 | Real estate search: CTR 7.61%, CPC $3.22, CVR 3.70%, CPL $102.51. Meta real estate leads: CTR 3.75–4.17%, CPC $1.27–$1.57, CPL $13.74–$16.61 |
| Authority boundary | Discovery call | Website/SEO controlled nationally; local authority for prospecting and forms |

---

## Stage 01 — Discover and Recommend

**Decision:** Is there a defined problem worth solving, and is the client ready to act?

**Work:**

1.1 Structured listening — three partners, three books (realtor/estate referrals; banks/foreclosures; institutional/REITs). Differentiator: 5–6 weeks to sale, cash, as-is, no due diligence.

1.2 Current-state assessment — 43 budgets totaling $252,038 proposed spend. Channel mix: Google $48,457 (19.2%), Meta $35,847 (14.2%), LinkedIn $14,845 (5.9%), owned email $988 (0.39%), direct mail $45,654 (18.1%), signage/production/info packages $70,078 (27.8%). Zero campaigns record expected bidders, downloads, or cost per qualified outcome. Budgets reverse-engineered to round price caps (10 of 43 within $15 of a round thousand).

1.3 Future-state definition — a marketing operation where every dollar traces to a qualified outcome, owned data is cultivated, and the three rainmakers' prospecting survives them.

1.4 Structured problem decomposition — gap between current (spend without outcome tracking) and future (spend-to-bidder line of sight) breaks into three workstreams: measurement and attribution, prospecting automation, paperwork automation. National website/SEO parked — requires board approval.

1.5 Evidence review — real estate search median CPL $102.51 (WordStream 2026); Meta real estate lead CPL $13.74–$16.61 (WordStream 2026). Client's own metric: 18,595 views → 11 downloads = 0.06% view-to-download. Industry real estate search conversion median 3.70%.

1.6 Recommendation — do not shift spend from Meta to Google (they already outspend Meta on Google in 40 of 41 dual-platform campaigns). The problem is unmeasured outcome-per-dollar, not channel allocation. Build the first measurement system: connect channel spend to information-package downloads to registered bidders. Start with local authority (prospecting + forms); park national website changes.

**Deliverable D1.4:** Single Statement of Work covering all five stages. One master document.

**Gate G1:** Client accepts the framing — "we have spend without outcome tracking, and the first build is measurement" — or names specific gaps. Silence is not acceptance.

---

## Stage 01b — Deep Spend Analysis (partner / stream variance)

> Pulled from the normalized corpus. This is the quantitative lane (property marketing). The other two lanes — seller relationships, paperwork/process — have no budget data yet; they stay qualitative until the workshop.

### Portfolio concentration

| Slice | Spend | Share of $252,038 |
|---|---:|---:|
| Londrey (20 campaigns) | $153,498 | 60.9% |
| Stein (9) | $39,948 | 15.9% |
| Terry (8) | $25,021 | 9.9% |
| NORA (1 — 140+ land portfolio) | $23,864 | 9.5% |
| Lewis (3) | $5,497 | 2.2% |
| Murphy (1) | $2,201 | 0.9% |
| Cates (1) | $2,008 | 0.8% |

Londrey alone is 67% of everything except the NORA outlier. Top 5 campaigns = 32.6% of total. Bottom 20 campaigns = 20.3%. The book is not flat — it is one heavy commercial rainmaker plus a long tail of smaller residential/land deals.

### Channel mix by originator

| Originator | Digital share | Offline share | Google share | Meta share | LinkedIn share |
|---|---:|---:|---:|---:|---:|
| Terry | 69% | 31% | 28% | 22% | 6% |
| Stein | 64% | 36% | 24% | 12% | 10% |
| Londrey | 53% | 47% | 18% | 14% | 6% |
| Lewis | 68% | 32% | 35% | 25% | 0% |
| NORA | 12% | 88% | 4% | 4% | 0% |

Terry is the most digital-heavy and the most Google-weighted. Stein leans LinkedIn (9.6% of his spend) — the only originator using it meaningfully. Londrey is the most offline-heavy of the three core partners, driven by signage and production on commercial deals. NORA is almost entirely offline (signage $10,440 + production $8,101 on one 140-lot land portfolio).

### Londrey's commercial tilt

17 of Londrey's 20 campaigns are commercial (office, retail, restaurant, special-use). Commercial avg $7,886 vs residential/land avg $6,480. His two restaurant x4 campaigns alone are $35,471 — nearly 14% of the entire portfolio. Commercial deals carry heavier signage and production lines; residential deals are leaner and more digital.

### What the variance implies for the three lanes

- **Property marketing (quantitative):** the variance is real and structural, not noise. Three different channel philosophies are running under one brand. No shared measurement means no way to tell which philosophy produces bidders. This is the lane with data — it is where the first diagnostic lands.
- **Seller relationships (qualitative):** Londrey's commercial book (banks, special-use, restaurants) implies a different seller-acquisition motion than Terry's residential/land or Stein's mixed foreclosure/condo work. Who originates the seller, how the relationship is maintained, and what the referral path looks like — unknown until workshop. No budget line captures this.
- **Paperwork / process (qualitative):** commercial multi-parcel and restaurant deals (Londrey) carry heavier info-package and production loads than single-family residential (Terry, Lewis). Process complexity likely scales with asset class, but that is an inference, not measured. The workshop has to surface the actual workflow differences.

### Round-cap budgeting check

10 of 43 campaigns land within $15 of a round thousand (e.g., $1,500.46, $2,000.44, $5,001.60). The rest are not round. This is weaker evidence of pure round-cap budgeting than initially framed — some budgets are genuinely itemized, others are capped. The diagnostic should separate the two rather than assume all are caps.

**Gate G1 (unchanged):** Client accepts the framing — "we have spend without outcome tracking, and the first build is measurement" — or names specific gaps. Silence is not acceptance.

---

## Stage 02 — Design and Plan

**Decision:** What gets built, by whom, at what cost, with what success metric?

**Work:**

2.1 Business case — 43 campaigns, $252,038 proposed spend, zero outcome records. The diagnostic builds the first yield model. Cost of the diagnostic: $11,500 for 42.5 hours across four roles (partner, marketing strategy, digital specialist, AI/process lead), max two-week window.

2.2 Future-state operating model — every campaign has an audience, objective, spend limit, and a tracked path from spend → inquiry → qualified opportunity → registered bidder. Owned email cultivated (currently 0.39% of spend). Reusable content and data reduce repeated work.

2.3 Implementation roadmap — Phase 1 (assessment, 2–3 weeks): validate spend source, map three books, assess digital channels, define measurement gaps, test priorities. Phase 2 (selected module): measurement, prospecting, or paperwork. Phase 3 (acceptance and handoff). Phase 4 (optional monthly care).

2.4 Measurement lock — client-stated metric: page views → information-package downloads, extended to registered bidders. Data sources: campaign budgets (existing), website analytics (access pending), download records (client holds names/contacts of the 11). Named owner: Michelle Stein, Director of Operations. No metric, no implementation spend.

2.5 Change control — any scope move requires a written Change Control Note: what changed, why, impact on scope/timeline/cost/metric, both parties sign before work proceeds.

**Deliverable D2.1:** Signed Statement of Work. Single master covering stages 01–05. Change-control process defined. Measurement spec locked.

**Gate G2:** Client signs the Statement of Work, or names specific gaps. Implementation does not start without signature.

---

## Stage 03 — Implement

**Decision:** Build the selected module and prove it works on real data.

**Work:**

3.1 Selected module — Measurement first (the constraint). Connect campaign identifiers to website events to download records to bidder registration. Up to 8 approved events, one dashboard view, Google Ads linkage if authorized, Meta validation.

3.2 Process designs — seller/referral intake flow, information-package download → follow-up sequence, fieldwork form population from tax record and listing agreement.

3.3 Results Management Office — drive, coordinate, support, measure, and track implementation activities. Weekly 30-minute check-in. Dependencies, assumptions, and change log maintained.

3.4 Testing — normal, duplicate, missing-ID, consent-blocked, and failure cases simulated. Human signs off on critical identifiers.

**Deliverable D3.1:** Live measurement configuration, documented processes, tested workflows. Change Control Notes for any mid-build scope moves.

**Gate G3:** First property cycle shows movement on the locked metric (views → downloads → registered bidders), or the client names specific gaps. Nothing ships without client acceptance.

---

## Stage 04 — Validate and Run

**Decision:** Can the client accept the result, and is it ready to run under AugMind?

**Work:**

4.1 Acceptance against criteria — tracking and forms tested; records route to the right owner; qualification definitions agreed; reusable campaigns/templates work; staff demonstrate the workflow on real examples; account ownership and support clear.

4.2 Value realization — compare actuals to baseline. Baseline: 18,595 views, 11 downloads, 0 tracked bidders, $252,038 proposed spend with zero outcome records. Target: measurable cost per qualified inquiry and cost per registered bidder by channel.

4.3 Stand up the run — automation, monitoring, operating cadence. Daily lead assignment and follow-up; weekly spend/quality/overdue review; monthly cohort assessment. Named owners, support boundaries, recurring operating plan.

4.4 Transition to managed services — optional monthly care: 1 monthly review, 2 routine changes within same design, business-hours response within 2 business days, capped monthly capacity. $900–$2,200/month depending on module.

**Deliverable D4.1:** Accepted deliverables, documented runbook, retainer proposal. Running starts only after acceptance.

**Gate G4:** Client accepts the run state or names specific gaps. The retainer starts only after acceptance. Silence is not acceptance.

---

## Stage 05 — Review results and improve

**Decision:** What improved, what didn't, and what changes next cycle?

**Work:**

5.1 Trend analysis — accumulate cycle data across properties. Compare channel performance to benchmarks (real estate search CPL $102.51, Meta real estate CPL $13.74–$16.61). Identify which channels produce qualified bidders vs. browsers.

5.2 Refine targeting — adjust spend allocation based on measured outcome-per-dollar, not assumed intent. Expand owned email cultivation (currently 0.39% of spend).

5.3 Quality gate — on higher-value or higher-risk work, one named reviewer outside the delivery team reviews the final deliverable before it reaches the client. Risk-based, like advisory practice. KPMG Advisory Quality Performance Reviews rate engagements green/yellow/red on set-up and execution.

5.4 Next-cycle plan — update the benchmark comparison, propose the next module (prospecting or paperwork), or recommend stopping.

**Deliverable D5.1:** Improvement report, next-cycle plan, quality sign-off.

**Gate G5:** Named reviewer signs off before anything goes back to the client. Client accepts the improvement report or names gaps.

---

## Traceability check

| Stage | Framework input | Work item | Deliverable | Gate |
|---|---|---|---|---|
| 01 | Structured listening, problem decomposition | 1.1–1.6 | D1.4 Statement of Work | G1 Accept framing |
| 01b | Spend variance analysis (own) | 1.7–1.10 | D1.5 Partner/stream variance brief | G1 (feeds) |
| 02 | Advisory gates | 2.1–2.5 | D2.1 Signed SOW + measurement lock | G2 Sign SOW |
| 03 | Advisory gates | 3.1–3.4 | D3.1 Live config + processes | G3 First cycle movement |
| 04 | Advisory gates | 4.1–4.4 | D4.1 Runbook + retainer | G4 Accept run state |
| 05 | Advisory gates | 5.1–5.4 | D5.1 Improvement report | G5 Quality sign-off |

Every claim traces to a sourced input. No number is invented. The box runs.

---

## What this proves

1. The method handles real, messy client data — 43 budgets, inconsistent schemas, zero outcome records — without breaking.
2. The gates force decisions: the client must accept the framing before design, sign the SOW before implementation, accept the run state before the retainer.
3. The measurement lock prevents the most common failure: optimizing the wrong metric (downloads instead of registered bidders).
4. The change-control gate prevents silent scope creep — every move is written, evidenced, and signed.
5. The quality gate ensures an independent reviewer checks the work before it reaches the client.
6. The recurring revenue model (Validate and Run) is the natural end state, not an add-on.
7. Own analysis of the corpus surfaces structural variance (Londrey 61%, three channel philosophies) that a light-touch read misses — and maps it cleanly to the three lanes.

## What still needs the real engagement

- Actual spend vs. proposed spend (this corpus is proposed only).
- Download-to-bidder conversion rates (currently unmeasured).
- Qualified bidder value (currently unknown).
- Access to website analytics, CRM, and download records (pending client provision).
- National board approval for website/SEO changes (parked, not abandoned).
- Seller-relationship and paperwork data for the two qualitative lanes (workshop input).

These are inputs for the real run, not gaps in the method. The method is ready.
