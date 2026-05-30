# UAT Entry and Exit Criteria

## UAT entry gate

A release should not enter UAT until the following are explicitly reviewed:

| Entry criterion | Ready condition | Evidence expected |
|---|---|---|
| Scope baseline | UAT scope is stable enough to test | Approved scope, backlog extract, release notes, or charter handoff |
| Test plan | Test scenarios and acceptance criteria are defined | Test plan, scenario list, traceability, acceptance criteria |
| Test data | Required data is available and fit for test use | Data readiness note, sample validation, refresh plan |
| Environment | Environment is accessible and stable enough for UAT | Environment status, access confirmation, integration readiness |
| Defect triage | Known defects are classified and understood | Defect list with severity, owner, workaround, decision needed |
| SME availability | Business validators are available | UAT calendar, named SMEs, backup owners |
| Signoff path | UAT signoff owners are identified | Signoff matrix |
| Operational readiness | Support or run-state owners know what is changing | Support readiness note, training plan, cutover notes |

## UAT exit gate

A release should not exit UAT or enter launch decision review until:

| Exit criterion | Ready condition | Evidence expected |
|---|---|---|
| Critical test coverage | Critical business paths tested | Executed tests, pass/fail summary, coverage trace |
| Defect position | No unresolved blocker lacks decision path | Defect triage, accepted residual risk, remediation plan |
| Evidence quality | Results are documented, not merely asserted | Test evidence, screenshots if appropriate, logs, approvals |
| Business acceptance | Business owner accepts UAT outcome | Signoff, meeting decision, written approval |
| Operational acceptance | Support and operations owners accept readiness | Support signoff, runbook summary, training evidence |
| Cutover readiness | Launch steps and rollback path are understood | Cutover plan, deployment plan, rollback note |
| Value follow-up | Post-launch measurement owner is named | Baseline/target handoff to value ledger |

## Criteria drafting rule

Use plain, auditable criteria. Avoid vague phrases such as "looks good," "mostly done," "minor bugs," or "team aligned." Replace them with observable conditions, named owners, due dates, and evidence.
