# Operating Model

## Purpose

This project helps human leaders decide whether a release is ready to enter UAT, exit UAT, launch, launch with conditions, or hold.

It is a readiness-governance aid. It is not a QA execution system, release automation tool, deployment checklist, test-management platform, or approval authority.

## Core review dimensions

1. Scope stability
2. UAT entry criteria
3. UAT exit criteria
4. Test coverage
5. Evidence quality
6. Defect and blocker status
7. Environment readiness
8. Data readiness
9. Integration and batch readiness
10. SME and business-owner availability
11. Support and operational readiness
12. Signoff ownership
13. Launch decision clarity
14. Downstream handoff completeness

## Readiness classification

Use four readiness states:

- **Ready** - Evidence is sufficient, owners are clear, risks are controlled, and no unresolved blocker prevents the next gate.
- **Ready with conditions** - The release may proceed only if specific named conditions are resolved or accepted by human owners before the next milestone.
- **Not ready** - One or more blockers, evidence gaps, unstable environments, material defects, or missing signoffs make the gate unsafe.
- **Insufficient evidence** - The available inputs do not support a credible readiness conclusion.

## Readiness score guidance

Use a 0-3 score per dimension:

- 3 = Ready; evidence present and accountable owner named.
- 2 = Mostly ready; manageable gap or risk with owner and due date.
- 1 = Weak; material gap, unclear owner, or late dependency.
- 0 = Blocked; gate cannot responsibly proceed without human decision or remediation.

Do not average away blockers. A single high-severity blocker can override an otherwise acceptable score.

## Evidence hierarchy

Prefer direct artifacts over assertions:

1. Signed or approved artifact
2. Current tracker or system extract
3. Named owner update with date
4. Meeting notes with decisions/actions
5. General verbal assertion
6. Assumption or inference

When evidence is weak, say so plainly.
