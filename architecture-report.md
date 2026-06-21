# Architecture Report

## Current State

Single Region Deployment

AWS Mumbai

Availability:
99.92%

---

## Future State

Active-Active Multi Region

Mumbai + Hyderabad

Availability:
99.99%

---

## Key Components

### Aurora PostgreSQL

Aurora Global Database

### DynamoDB

Global Tables

### Redis

Cross Region Replica

### Kafka

MSK + MirrorMaker 2

### Networking

Route53
Global Accelerator

---

## Recovery Objectives

RPO:
< 1 Minute

RTO:
< 5 Minutes

---

## Outcome

Resilient payment platform capable of handling regional outages with minimal disruption.