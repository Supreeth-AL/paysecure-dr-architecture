# Project Summary

PaySecure Gateway Private Limited required a disaster recovery architecture capable of achieving:

- 99.99% uptime
- RPO under 1 minute
- RTO under 5 minutes

The proposed solution uses an Active-Active multi-region architecture across AWS Mumbai and AWS Hyderabad.

Key technologies include:

- Aurora Global Database
- DynamoDB Global Tables
- ElastiCache Redis
- Amazon MSK
- Route53
- Global Accelerator
- CloudWatch

The architecture aligns with RBI, PCI-DSS, NPCI, and Data Localization requirements while providing high availability and operational resilience.