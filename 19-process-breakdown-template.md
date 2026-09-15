# 19 — Process Breakdown Template (manual → automated)

Use this for any client process. Documentation standard: BPMN 2.0 / ISO/IEC 19510. Advisory overlay: KPMG baseline + Deloitte workflow redesign.

## Required artifacts per process
1. Current-state process map (numbered steps, swim lanes, systems, handoffs, decision diamonds).
2. Activity and effort baseline (minutes/step, FTE/month, cost/step, error rate).
3. Future-state process map (same numbering where steps survive; mark Eliminate / Automate / Assist / Human-only).
4. Automation opportunity sizing (hours saved, accuracy target, payback).
5. RACI for redesigned steps.
6. Target operating model snippet (who owns, what system of record, exception path).
7. Implementation roadmap slice.
8. Runbook + measurement lock.

## Baseline effort table (fill per process)
| Step # | Name | Actor | System | Minutes now | Minutes target | Error rate now | Error rate target | Decision? | Handoff to |
|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | Y/N | |

## Savings model
Hours saved/month = (minutes now − minutes target) × volume / 60.
Cost saved/month = hours saved × loaded rate.
Do not count auction-platform time as savings if the platform already runs it.

## Redesign questions (Deloitte)
- Who should do the work?
- Which steps can be eliminated?
- How should the sequence change?
- Where does human authority remain?
- What happens when the model is uncertain or wrong?

## RACI columns
Responsible, Accountable, Consulted, Informed — one Accountable per step.
