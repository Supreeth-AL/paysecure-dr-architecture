# ADR-001

## Title

Selection of Active-Active Multi-Region Disaster Recovery Strategy

## Status

Approved

## Context

PaySecure must achieve:

- 99.99% uptime
- RPO under 1 minute
- RTO under 5 minutes

## Decision

Implement Active-Active deployment across:

- AWS Mumbai
- AWS Hyderabad

## Consequences

Positive:
- High availability
- Fast failover
- Better scalability

Negative:
- Increased complexity
- Increased cost