# Prior Authorization Proof

## Purpose

This proof example shows how prior authorization functions as a coordination workflow across patient access, payer rules, clinical documentation, status tracking, and final account clearance.

## Core Insight

Prior authorization is not just a payer requirement. It is a workflow visibility problem when ownership, documentation, and timing are unclear.

## Workflow Map

```text
Patient Scheduled
  |
  v
Service Identified
  |
  v
Payer Rules Reviewed
  |
  v
Authorization Requirement Confirmed
  |
  v
Documentation Collected
  |
  v
Authorization Submitted
  |
  v
Status Tracked
  |
  v
Approval Verified
  |
  v
Account Cleared
```

## Common Failure Points

| Failure Point | Downstream Risk | Prevention Action |
|---|---|---|
| Requirement not checked | Missing authorization denial | Check payer rules before appointment confirmation |
| Documentation incomplete | Authorization delay or denial | Use documentation readiness checklist |
| Pending status not tracked | Appointment may occur before approval | Use authorization workqueue by service date |
| Approval details missing | Claim denial or billing rework | Verify approval number and date range |
| Handoff unclear | Duplicate work or missed follow-up | Create standardized status handoff note |

## Metric to Track

Authorization-related denial rate, average authorization turnaround time, pending authorizations by service date, and authorization rework volume.

## Created By

Created by Kori Pickle
