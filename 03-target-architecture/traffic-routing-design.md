# Traffic Routing Design

## Normal State

Traffic Distribution:

Mumbai:
50%

Hyderabad:
50%

---

## Mumbai Failure

Traffic Distribution:

Mumbai:
0%

Hyderabad:
100%

---

## Hyderabad Failure

Traffic Distribution:

Mumbai:
100%

Hyderabad:
0%

---

## Routing Method

AWS Global Accelerator

Health Checks:
Every 30 Seconds