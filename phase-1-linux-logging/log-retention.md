# Log Retention Observation

## Observation
At the time of review, only recent logs were readily visible for certain components.

## Assessment
Default log rotation and service restarts can limit historical visibility on lightweight systems. This is typical for small Linux hosts unless retention is explicitly configured.

## Risk Consideration
Limited retention can reduce the ability to perform historical review and delayed incident investigation.

## Control Alignment (NIST 800-53)
- AU-11 (Audit Record Retention)
- AU-4 (Audit Storage Capacity)

## Status
Documented as a baseline constraint. Retention tuning is a candidate for a follow-on hardening phase.
