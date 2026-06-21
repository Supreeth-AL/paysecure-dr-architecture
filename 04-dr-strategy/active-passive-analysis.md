# Active-Passive Architecture Analysis

## Architecture

Primary Region:
AWS Mumbai (ap-south-1)

Secondary Region:
AWS Hyderabad (ap-south-2)

Traffic Flow:

Users
  |
  |
Mumbai (Active)
  |
Replication
  |
Hyderabad (Passive)

---

## Advantages

- Lower infrastructure cost
- Simpler architecture
- Easier operations

---

## Disadvantages

- Failover delay
- Higher operational risk
- RTO may exceed target during complex failures

---

## RPO Assessment

Estimated:
30 seconds to 1 minute

Status:
PASS

---

## RTO Assessment

Estimated:
3-10 minutes

Status:
RISK

---

## RBI Assessment

Partially compliant.

---

## Recommendation

Possible but not ideal.