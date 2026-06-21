# RB-03 Aurora Failover

## Incident

Primary Aurora Cluster Failure

## Severity

P1 Critical

## Detection

CloudWatch Alarm

## Recovery Steps

1. Promote Hyderabad Reader

2. Update Application Endpoint

3. Verify Connections

4. Resume Writes

## Validation

Successful Test Transaction

## Closure Criteria

New Writer Operational