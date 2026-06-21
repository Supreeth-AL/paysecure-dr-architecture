# ADR-003

## Title

DynamoDB Global Tables Strategy

## Decision

Implement Global Tables

Regions:

- Mumbai
- Hyderabad

---

## Benefits

- Near Zero RPO
- Sub Minute RTO
- Active-Active Operation
- Automatic Synchronization

---

## Risks

Conflict Resolution

---

## Mitigation

Last Writer Wins
Audit Logging
Monitoring