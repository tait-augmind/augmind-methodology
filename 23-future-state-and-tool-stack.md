# 23 — Future State and Named Tool Stack

**Rule:** Redesign the workflow first. Tools sit on the redesigned steps. Do not layer tools on broken handoffs.

## Systems of record (keep to three)
1. CRM — HubSpot or Pipedrive.
2. Documents — PandaDoc or DocuSign.
3. Lightweight ops database — Airtable or Notion.
Glue: Zapier or Make.

## Property intake — future
- Web form instead of shared inbox.
- Zapier/Make creates CRM record.
- Tax lookup via ATTOM or Regrid API (replaces 30–90 min browser pull).
- PandaDoc listing agreement pre-filled from CRM.
- Stalled signatures: automated reminder sequence.

## Marketing — future
- Template library keyed to asset class.
- Channel-mix rule: digital-heavy under $50k expected GMV, mixed above; human approves.
- Landing pages: Unbounce or Webflow with A/B tests.
- Email layer: HubSpot or ActiveCampaign (currently ~0.4% of spend).
- UTM taxonomy enforced at source.
- Attribution: Northbeam, Triple Whale, or GA4 + CRM source fields if budget is tight.
- Google Ads + Meta Ads Manager remain; they are not the gap.

## Buyer engagement — future
- Registration form writes a CRM contact with source, campaign, property ID.
- Retargeting driven by CRM segments, not guesswork.
- Drip: 3 touches over 14 days; human only for warm leads.

## Auction execution — future
- Unchanged. Platform already does this.

## Post-sale — future
- Make scenario parses auction export CSV → updates CRM/Airtable.
- PandaDoc contract auto-populated.
- Plaid or bank-feed match for reconciliation.
- Seller report generated from the same record. No second pass.

## Measurement architecture (Lane A lock)
Events: page view, package download, registration, first bid, hammer, close.
Primary KPIs: visitor-to-registration, registration-to-bidder, cost per registered bidder, cost per hammer dollar.
Owner named. Source system named. No silent metric changes — use Change Control Note.
