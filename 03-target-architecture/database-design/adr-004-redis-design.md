# ADR-004

## Title

Redis Disaster Recovery Design

## Decision

Primary Replica Architecture

Mumbai:
Primary

Hyderabad:
Replica

---

## Benefits

- Fast Failover
- Simpler Operations
- Supports RTO < 1 Minute

---

## Risks

Temporary Cache Loss

---

## Mitigation

Cache Rebuild Strategy
Cross Region Snapshots