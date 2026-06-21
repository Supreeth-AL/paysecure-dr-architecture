# Split Brain Prevention

## Risk

Both regions accept writes simultaneously.

Result:

Data inconsistency.

---

## Prevention Strategy

Single Writer Model

Writer:
Mumbai

Reader:
Hyderabad

---

## Failover Event

Mumbai Failure

Promote Hyderabad Reader

Hyderabad becomes Writer

---

## Failback Event

Mumbai restored

Mumbai becomes Reader

Controlled switchover required.