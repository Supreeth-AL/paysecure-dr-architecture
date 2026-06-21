# Automated Failover Design

## Event

Mumbai Region Failure

---

## Detection

CloudWatch Alarm

---

## Trigger

EventBridge Rule

---

## Action

Lambda Function

---

## Activities

1. Verify Failure

2. Promote Aurora Replica

3. Redirect Route53

4. Update Global Accelerator

5. Notify Operations Team

---

## Target RTO

Under 5 Minutes