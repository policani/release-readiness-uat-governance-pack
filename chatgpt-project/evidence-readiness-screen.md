# Evidence Readiness Screen

## Purpose

Determine whether the readiness claim is supported by usable evidence.

## Evidence dimensions

Score each 0-3:

| Dimension | 3 - Strong | 2 - Adequate | 1 - Weak | 0 - Missing/blocking |
|---|---|---|---|---|
| Traceability | Tests map to requirements/processes | Key paths mapped | Partial mapping | No mapping |
| Test execution | Executed results current | Most results current | Results stale or partial | No execution evidence |
| Defect evidence | Defects triaged with owners | Mostly triaged | Severity/owner unclear | Blockers untriaged |
| Business validation | Named owners reviewed results | Some owner review | Informal review only | No business review |
| Operational evidence | Support/run evidence present | Partial support review | Assumed readiness | No operational review |
| Decision evidence | Decisions recorded | Most decisions recorded | Decision history unclear | No decision record |

## Evidence gap output

For each gap, state:

- Gap
- Why it matters
- Evidence needed
- Owner
- Due date
- Gate impact
- Escalation path if unresolved

## Confidence ratings

Use:

- **High confidence** - Current, direct evidence supports the readiness claim.
- **Moderate confidence** - Evidence is mostly present but has timing, coverage, or ownership gaps.
- **Low confidence** - Important claims rely on assertions, stale updates, or incomplete artifacts.
- **No confidence** - The available evidence does not support a readiness conclusion.

## Failure signals

Flag these immediately:

- Green status with no test evidence
- Critical path not traced to test cases
- Defect counts without severity or owner
- UAT dates fixed while SMEs are unavailable
- Environment declared ready despite unresolved instability
- Signoff owner not named
- "Known issue" with no acceptance authority
