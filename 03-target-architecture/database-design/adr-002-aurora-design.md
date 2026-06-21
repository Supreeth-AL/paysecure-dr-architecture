# ADR-002

## Title

Aurora PostgreSQL DR Architecture

## Decision

Use Aurora Global Database

Primary:
Mumbai

Secondary:
Hyderabad

## Reason

Supports:

- 99.99% Availability
- RPO < 1 Minute
- RTO < 5 Minutes

## Risks

Cross-region dependency

## Mitigation

Continuous monitoring and automated failover.