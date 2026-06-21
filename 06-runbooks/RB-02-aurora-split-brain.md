# RB-02 Aurora Split Brain

## Incident

Multiple Writers Detected

## Severity

P1 Critical

## Detection

Replication Conflict Alert

## Verification

Check Writer Endpoint

Check Replication Status

## Recovery Steps

1. Freeze Writes

2. Identify Authoritative Writer

3. Disable Secondary Writes

4. Reconcile Conflicting Records

5. Resume Processing

## Validation

Database Consistency Check

## Escalation

Database Team

Chief Architect

## Closure Criteria

Single Writer Restored