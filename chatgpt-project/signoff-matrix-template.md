# Signoff Matrix Template

## Purpose

Make signoff ownership explicit before UAT exit or launch decision review.

## Signoff matrix

| Signoff area | Accountable owner | Required decision | Evidence required | Status | Notes |
|---|---|---|---|---|---|
| Business process |  | Accepts business validation result | UAT summary, process test evidence |  |  |
| QA/test |  | Confirms test evidence and defect position | Test execution and defect report |  |  |
| Technology/application |  | Confirms technical release readiness | Release notes, deployment readiness |  |  |
| Environment/data |  | Confirms environment and data are fit | Environment/data readiness summary |  |  |
| Operations/support |  | Confirms run-state readiness | Support plan, runbook, training note |  |  |
| Finance/accounting |  | Confirms finance-impacting controls where applicable | Reconciliation or accounting validation evidence |  |  |
| Security/privacy/compliance |  | Confirms required control review where applicable | Control signoff or documented non-applicability |  |  |
| Sponsor/executive |  | Makes launch, hold, or conditional decision | Launch decision brief |  |  |

## Signoff rules

- Do not invent signoff owners.
- Do not infer approval from silence.
- Do not treat attendance as signoff.
- Do not treat a status color as approval.
- Do not collapse multiple accountable areas into one owner unless the user confirms authority.
- State when signoff is missing, informal, or outside this module's authority.

## Human authority

Only accountable humans can approve release, accept defects, waive controls, or accept residual risk.
