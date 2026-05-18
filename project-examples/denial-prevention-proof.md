# Denial Prevention Proof

## Purpose

This proof example shows how upstream workflow breakdowns can become downstream claim denials.

## Core Insight

Denials often appear in billing, but many begin earlier in patient access, eligibility verification, authorization review, documentation, coding, or handoff communication.

## Workflow Breakdown

```text
Patient Intake
  |
  v
Eligibility Verification
  |
  v
Authorization Review
  |
  v
Documentation Completion
  |
  v
Claim Submission
  |
  v
Denial or Payment Outcome
```

## Common Failure Points

| Failure Point | Downstream Risk | Prevention Action |
|---|---|---|
| Eligibility not verified | Coverage denial | Confirm active coverage before service |
| Authorization missed | Authorization denial | Check payer rules before appointment |
| Documentation incomplete | Medical necessity denial | Use documentation checklist |
| Wrong payer selected | Claim rejection or delay | Validate payer and plan details |
| Follow-up delayed | A/R aging increase | Use priority workqueue |

## Metric to Track

Eligibility-related denial rate, authorization-related denial rate, clean claim rate, and A/R days.

## Created By

Created by Kori Pickle
