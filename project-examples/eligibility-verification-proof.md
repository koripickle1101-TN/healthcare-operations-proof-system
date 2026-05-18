# Eligibility Verification Proof

## Purpose

This proof example shows how eligibility verification protects clean claim readiness before the patient encounter happens.

## Core Insight

Eligibility verification is not just a registration task. It is an upstream revenue cycle checkpoint that affects denials, patient billing clarity, authorization requirements, and A/R workload.

## Workflow Map

```text
Patient Scheduled
  |
  v
Insurance Information Collected
  |
  v
Coverage Status Verified
  |
  v
Payer and Plan Validated
  |
  v
Coordination of Benefits Reviewed
  |
  v
Authorization Requirement Checked
  |
  v
Account Cleared Before Service
```

## Common Failure Points

| Failure Point | Downstream Risk | Prevention Action |
|---|---|---|
| Inactive coverage | Claim denial | Confirm active coverage for date of service |
| Wrong member ID | Claim rejection | Validate member ID with payer record |
| Wrong payer selected | Incorrect claim routing | Confirm payer and plan type |
| COB not reviewed | COB denial | Review primary and secondary coverage |
| Authorization requirement missed | Authorization denial | Check payer rules before service |

## Metric to Track

Eligibility-related denial rate, registration error rate, clean claim rate, and financially cleared account percentage.

## Created By

Created by Kori Pickle
