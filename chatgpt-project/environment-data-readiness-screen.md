# Environment and Data Readiness Screen

## Purpose

Identify whether the test or launch environment, data, access, integrations, and operational dependencies support credible validation.

## Review areas

| Area | Review questions |
|---|---|
| Environment access | Do all testers and SMEs have access? Are roles and permissions correct? |
| Stability | Has the environment been stable long enough for useful testing? |
| Configuration | Does configuration match the intended release scope? |
| Test data | Is data realistic, complete, refreshed, masked when required, and available when needed? |
| Integrations | Are upstream and downstream interfaces available and testable? |
| Batch/scheduled jobs | Are scheduled jobs configured, monitored, and testable? |
| Performance constraints | Are there known capacity, latency, or timing issues that affect validation? |
| Cutover dependency | Are cutover sequence, rollback path, and support coverage understood? |
| Ownership | Is each dependency owned by a named accountable person? |

## Classification

- **Ready** - Required environment/data dependencies are available and stable.
- **Ready with conditions** - Specific known gaps have owners and dates before the gate.
- **Not ready** - Instability, access, data, integration, or batch dependency prevents credible testing or launch.
- **Insufficient evidence** - The team cannot support its readiness claim.

## Output format

### Environment and data readiness

| Dependency | Status | Evidence | Owner | Due date | Gate impact |
|---|---|---|---|---|---|

### Material risks

List only risks that can affect UAT entry, UAT exit, launch, customer/business impact, finance/accounting validation, compliance, or support readiness.
