# 04 — Red-Team Notes

- SPIN removed — sales methodology, not advisory.
- Hypothesis tree removed — McKinsey/BCG/Bain, not Big Four.
- "Attestor" replaced with "owner" — advisory framing.
- No audit language anywhere.
- Every claim has a link or is labeled as a placeholder pending real data.

## QC Pass 1 — Source Corrections (recursive loop)
- Stage 03 Results Management Office: corrected from an unverified Iowa Regents proposal PDF to the verified Deloitte case study "Reshaping an IT Operating Model Journey."
- Stage 04 Evolve / recurring model: corrected from a broken KPMG client-story URL to the verified Powered Enterprise page and Powered Evolution PDF.
- Stage 05 quality gate: corrected from a broken KPMG Integrated Report URL to the verified quality-management page (https://corporatereporting.kpmg.nl/search/2023_035).
- Change Control Note template: corrected from a 2024 Deloitte terms PDF to the verified March 2025 Schedule 4.
- Runbook template: corrected recurring-model citations to the verified Powered Enterprise and Powered Evolution sources.
- Main evidence base: added the verified Deloitte RMO, change-control, Powered Enterprise, and Powered Evolution links.

## QC Pass 2 — Practitioner Check (recursive loop)
- Stage 02 change-control source: corrected from a 2024 Deloitte terms PDF (which only covered Statement of Work signing) to the verified March 2025 Schedule 4, which contains the actual Change Control Note (CCN) language: both parties execute two copies, the SOW is amended upon execution, and work performed without a CCN is at the Supplier's sole risk. https://www.deloitte.com/content/dam/assets-zone2/uk/en/docs/about/2025/deloitte-uk-supplier-terms-and-conditions-march-2025.pdf
- Change Control Note template (10): updated to cite the same verified March 2025 Schedule 4 CCN language, including the exact execution and risk clauses.
- Practitioner test: a real advisory engagement can fill the CCN fields — what changed, why, impact on scope/timeline/cost/metric, evidence, decision, both signatures — using only what a client would hand over. No fabricated fields.
- Remaining open item: the "drive, coordinate, support, measure, and track" phrasing for the Results Management Office is a synthesis of Deloitte RMO case-study language, not a verbatim quote. Labeled as such; acceptable for advisory framing but flagged for a future verbatim source if one is found.

## QC Pass 3 — Adversary Check (recursive loop)
Skeptical-client challenges and responses. Each challenge is stated as the client would say it; the response is what the method actually says.

1. "Why should I sign a Statement of Work covering all five stages before you've done any work?"
   Response: The Statement of Work defines the engagement, not a blank check. Gate G1 is where you accept the recommendation or name gaps. Gate G2 is where you sign the plan. Gate G3 is where the first cycle must show movement. Gate G4 is where you accept the run state. Gate G5 is where the reviewer signs off. You can stop at any gate. Silence is not acceptance — Deloitte's own terms require a signed Statement of Work before it is binding. https://www.deloitte.com/content/dam/assets-zone2/uk/en/docs/about/2025/deloitte-uk-supplier-terms-and-conditions-march-2025.pdf

2. "This looks like a lot of process for a small engagement."
   Response: The quality gate is risk-based, not mandatory on every job. KPMG Advisory Quality Performance Reviews rate engagements green, yellow, or red; both green and yellow are satisfactory. One named reviewer outside the delivery team reviews higher-value or higher-risk work only. https://corporatereporting.kpmg.nl/search/2023_035

3. "You're charging me to run things after delivery. That's not consulting."
   Response: The run model is the recurring revenue engine, not a handoff. KPMG Powered Enterprise Evolve phase: "Complete post go-live support, value realization analysis, project closure procedures and transition to managed services programs, as applicable." KPMG Powered Evolution is a managed service delivered through a multi-year subscription with predictable costs. https://kpmg.com/us/en/capabilities-services/advisory-services/kpmg-powered-enterprise.html

4. "What if the metric you locked doesn't move?"
   Response: Gate G3 requires the first cycle to show movement on the locked metric. If it doesn't, the gate fails and the engagement stops or pivots under change control. No silent pivots — a written Change Control Note is required for any scope move, with impact assessed and both sides signing. https://www.deloitte.com/content/dam/assets-zone2/uk/en/docs/about/2025/deloitte-uk-supplier-terms-and-conditions-march-2025.pdf

5. "Who checks your work before it reaches me?"
   Response: On higher-value or higher-risk work, one named person outside the delivery team reviews the final deliverable before it goes to the client. This mirrors KPMG Advisory practice where the Functional Quality & Risk Management Partner performs Quality Performance Reviews. It is not an audit attestation — it is an advisory quality review. https://corporatereporting.kpmg.nl/search/2023_035

Adversary verdict: the method survives the skeptical client. Every challenge maps to a gate, a source, or a documented control. No claim is unanswerable.
