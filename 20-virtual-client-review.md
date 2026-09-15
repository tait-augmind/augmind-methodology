# 20 — Virtual Client Review

**Reviewer:** Virtual Client — Northbridge Auctions, skeptical CFO/COO  
**Standard:** Typical mid-market advisory engagement for a regional real-estate auction firm; accurate, defensible, implementable, not over-engineered.

## Verdict
Conditionally accepted. Directionally accurate and more rigorous than typical boutique material. Required before client-ready: process baseline/RACI, measurement architecture, referral operating model, document automation controls, retainer service catalog.

## Findings

**R1 High — Process transformation.** Template was strong on current/future state but needed quantified effort (hours/FTE/cost) and RACI. Fix: baseline + target effort tables and RACI in `19-process-breakdown-template.md`.

**R2 High — Lane A marketing.** Channel-shift narrative is weaker than measurement integrity. Fix: UTM taxonomy, event tracking, bidder registration, cost-per-registered-bidder, cost-per-hammer, attribution by asset class/originator. See `23-future-state-and-tool-stack.md`.

**R3 Medium — Lane B relationships.** Too qualitative. Fix: ICP, 12-touch sequence, CRM schema, referral-fee waterfall, KPI tree in `16-lane-b-seller-referral-relationships.md`.

**R4 Medium — Lane C paperwork.** Named forms without field dictionary, confidence thresholds, exception queue, audit trail. Fix: document inventory and controls in `22` and `23`.

**R5 Medium — Pricing.** Retainer needed a service catalog and SLAs. Fix: `18-staffing-and-pricing-synthetic.md`.

**R6 Low — Evidence.** Every modeled KPI should cite benchmark + range + confidence. Fix: keep citations in `03-evidence-library.md` and `14`.

**R7 Low — Change control.** CCN should include impact on metric, data, automation, and retainer fee.

## Next actions after a live client
Replace modeled figures with campaign, download, bidder, and hammer data at Stage 03. Re-run this review against live numbers.
