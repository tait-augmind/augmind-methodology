# 22 — BPMN Process Maps (text; drop into Visio/Lucidchart)

**Notation:** BPMN 2.0 / ISO/IEC 19510. Each step has number, swim lane, technology, handoff, and decision diamonds where the flow branches.
**Process source:** NAA contract-to-close + published auction-house SOP guides.

Legend: (S) Seller (O) Originator (M) Marketing (BO) Back Office (IT) IT System (B) Buyer

## Process 1 — Property intake (9 steps)
1. (S) calls or emails. (O) answers. Handoff: lead in shared inbox. No CRM.
2. (O) qualifies type, location, motivation, timeline. Diamond: engage or decline.
3. (O) pulls tax records manually (browser/phone). 30–90 min.
4. (O) drafts listing agreement. (BO) reviews. Handoff: agreement to (S).
5. (S) signs. (BO) files. Diamond: signed or stalled. Stalled has no reminder sequence today.
6. (O)+(S) set price cap/reserve. (BO) logs. Handoff: marketing queue.
7. (M) receives brief. Diamond: standard campaign or custom.
8. (BO) creates seller dashboard entry. (IT) generates listing page. Handoff: property live.
9. (O) confirms go-live with (S). End.

Bottlenecks: 3, 5, 7.

## Process 2 — Marketing and listing (10 steps)
1. (M) receives brief from (BO). Shared folder/email.
2. (M) selects template by asset class. Diamond: standard or custom.
3. (M) drafts creatives. 2–4 hours.
4. (M) sets channel mix. Diamond: digital-heavy or mixed.
5. (M) places ads (Google Ads, Meta Ads Manager, print vendor). Handoff: ads live.
6. (IT) generates listing page + seller dashboard. Handoff: page public.
7. (M) monitors daily. Diamond: on track or underperforming.
8. (M) sends information package. Email/PDF. No open/download person-level tracking.
9. (M) logs results in dashboard.
10. (M) closes campaign at auction day. End.

Bottlenecks: 3, 4, 7, 8.

## Process 3 — Buyer engagement (8 steps)
1. (B) finds listing (Google/Meta/mail/referral).
2. (IT) listing page. Diamond: bounce or engage.
3. (B) downloads package. Logged as a count, not a person.
4. (B) registers to bid. Spreadsheet, not CRM.
5. (O) calls/emails registered buyer. Diamond: warm or cold. Cold gets nothing.
6. (M) retargets engaged buyers (Meta/Google).
7. (B) attends auction. Diamond: bids or watches.
8. (BO) logs results. Channel source often missing because step 3 never captured a person.

Bottlenecks: 3, 4, 5.

## Process 4 — Auction execution (7 steps)
1. Auction live. (IT) platform.
2. Bidding opens. Diamond: bid or pass.
3. Bidding escalates. Automated engine.
4. Hammer. Diamond: sold or passed in.
5. Results captured. Platform export.
6. (O) notifies (S).
7. Settlement begins. Manual re-key into contracts.

Do not rebuild the bidding engine. Bottleneck is step 7 handoff.

## Process 5 — Post-sale and paperwork (9 steps)
1. (BO) receives auction export in inbox.
2. (BO) re-keys buyer/property into purchase contract. 45 min–2 hr. Diamond: standard or custom terms.
3. Contract to (B). Email / sometimes DocuSign. No reminder sequence.
4. (B) signs. Diamond: signed or stalled.
5. (BO) compiles data sheet for (M) — same fields re-entered.
6. Settlement coordination with title/escrow/attorney. Lives in email.
7. Funds received and reconciled by hand (bank portal + spreadsheet).
8. (O) generates seller report. Diamond: satisfied or questions.
9. Files archived to shared drive. No version control. End.

Bottlenecks: 2, 5, 7.

## Pattern
Handoffs lose data. Manual steps duplicate work. Rainmakers are the relationship system of record.
