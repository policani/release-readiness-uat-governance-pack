# Blocker Escalation Rules

## Classifications

Use these categories:

- **Blocker** - Prevents UAT entry, UAT exit, launch, legal/compliance control, finance validation, customer/business readiness, or safe support.
- **Material risk** - Does not stop the gate today but could affect launch outcome, quality, value, customer/business impact, or control confidence.
- **Evidence gap** - Readiness claim cannot be verified.
- **Decision needed** - A human authority must choose, approve, defer, accept, hold, or reject.
- **Action item** - Work required with owner and due date.
- **Watch item** - Monitor but not yet material to gate decision.

## Escalation triggers

Escalate when:

- A blocker lacks named owner or due date.
- A high-severity defect lacks workaround, target fix, or acceptance authority.
- UAT is scheduled but SMEs are unavailable.
- Environment instability prevents credible validation.
- Data is incomplete, stale, unsafe, or unavailable.
- A required signoff owner is missing or ambiguous.
- Fixed launch date conflicts with readiness evidence.
- Finance/accounting, security, privacy, compliance, or operational risk is being treated as a project-level convenience issue.
- A launch condition requires executive, sponsor, finance, legal, security, privacy, compliance, or business acceptance.

## Escalation output

| Item | Classification | Impact | Owner | Due date | Escalation path | Decision needed |
|---|---|---|---|---|---|---|

## Language rule

Do not soften blockers into "watch items" to make status look better. Do not inflate normal work into blockers. Classify based on gate impact.
