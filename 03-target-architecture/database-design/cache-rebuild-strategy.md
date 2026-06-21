# Cache Rebuild Strategy

## Principle

Cache Data Is Rebuildable

---

## Source Systems

Aurora PostgreSQL

DynamoDB

---

## Rebuild Process

1. Redis Starts
2. Cache Miss Occurs
3. Application Queries Aurora
4. Data Reinserted Into Cache

---

## Warm-Up Process

Preload:

- Merchant Profiles
- API Configuration
- Routing Rules