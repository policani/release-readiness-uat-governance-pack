# Trigger Map

Use this file to route user requests to the right runtime files.

## Trigger: start readiness review

User says: start, assess readiness, UAT readiness, release readiness, launch readiness, go/no-go, validation gate.

Load:
- `release-readiness-intake.md`
- `uat-entry-exit-criteria.md`
- `quality-review-rubric.md`

Output:
- Intake summary
- Missing information request
- Initial readiness review path

## Trigger: define UAT gates

User asks for entry criteria, exit criteria, validation criteria, acceptance criteria, gate checklist.

Load:
- `uat-entry-exit-criteria.md`
- `evidence-readiness-screen.md`

Output:
- Entry criteria
- Exit criteria
- Evidence required
- Human signoff points

## Trigger: review evidence quality

User provides test cases, defect notes, traceability, screenshots, status notes, acceptance criteria, or coverage summary.

Load:
- `evidence-readiness-screen.md`
- `quality-review-rubric.md`

Output:
- Evidence gap list
- Coverage concerns
- Confidence rating
- Required follow-ups

## Trigger: review environments or data

User mentions environment instability, test data, integrations, batch jobs, access, refreshes, cutover, upstream/downstream systems.

Load:
- `environment-data-readiness-screen.md`
- `blocker-escalation-rules.md`

Output:
- Environment/data readiness screen
- Blockers and dependencies
- Escalation recommendations

## Trigger: signoff or ownership

User asks who signs off, which owners are needed, RACI, approval matrix, signoff gaps.

Load:
- `signoff-matrix-template.md`
- `privacy-human-control.md`

Output:
- Signoff matrix
- Ownership gaps
- Decisions humans must make

## Trigger: blockers and defects

User mentions defects, open bugs, blockers, Sev 1/2, workaround, risk acceptance, launch risk.

Load:
- `blocker-escalation-rules.md`
- `launch-brief-template.md`

Output:
- Blocker escalation list
- Decision needed
- Launch impact

## Trigger: build launch brief

User asks for executive summary, launch decision, go/no-go brief, sponsor update.

Load:
- `launch-brief-template.md`
- `handoff-rules.md`
- `quality-review-rubric.md`

Output:
- Launch decision brief
- Human-owned decision table
- Handoff summary
