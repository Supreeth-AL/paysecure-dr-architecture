# PaySecure Gateway Pvt Ltd

## Current Environment

### Region

AWS Mumbai (ap-south-1)

### Availability

99.92%

### Daily Volume

3.2 Million Transactions

### Daily Value

₹500 Crore

### Merchants

45,000

---

## Existing Architecture

Single AWS Region Deployment

Region:
ap-south-1 (Mumbai)

Components:

- Application Servers
- Aurora PostgreSQL
- DynamoDB
- Redis
- Kafka
- Payment Processing APIs

---

## Current Risks

1. Region Failure
2. Database Failure
3. Kafka Failure
4. Redis Failure
5. Network Isolation
6. Capacity Exhaustion