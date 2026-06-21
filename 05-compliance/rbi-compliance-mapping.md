# RBI Compliance Mapping

## Regulation

RBI Master Direction on Payment Systems

---

## Requirement

Business Continuity Planning

Implementation:

- Active-Active Multi Region
- Mumbai Region
- Hyderabad Region

Status:

Compliant

---

## Requirement

Disaster Recovery Site

Implementation:

- Secondary Region
- Automated Failover

Status:

Compliant

---

## Requirement

Recovery Time Objective

Target:

Under 5 Minutes

Implementation:

CloudWatch + Lambda Failover

Status:

Compliant

---

## Requirement

Recovery Point Objective

Target:

Under 1 Minute

Implementation:

Aurora Global Database
DynamoDB Global Tables
Kafka Replication

Status:

Compliant