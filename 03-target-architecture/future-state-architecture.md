# Future State Architecture

## Deployment Model

Active-Active

## Regions

Primary Region:
AWS Mumbai (ap-south-1)

Secondary Region:
AWS Hyderabad (ap-south-2)

Both regions process production traffic.

---

## Core Components

- Route53
- AWS Global Accelerator
- Application Load Balancer
- Auto Scaling Groups
- Aurora PostgreSQL
- DynamoDB
- ElastiCache Redis
- Apache Kafka (MSK)
- CloudWatch
- AWS Backup