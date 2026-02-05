# Linux Logging Overview (ISSO Baseline)

## Purpose
Establish a baseline understanding of where security-relevant events are logged on Linux and how to retrieve evidence for audits and reviews.

## Primary Log Source
- systemd journal (journald)
- Service logs accessed via `journalctl`

## Security-Relevant Event Categories
### Authentication (SSH)
- Successful logins
- Failed logins
- Invalid users
- Source IP addresses

### Privilege Use (sudo)
- User elevation activity
- Administrative command execution

### Availability / System Events
- Service restarts
- Reboots and unexpected interruptions

## Evidence Collection Methods
- `journalctl -u ssh` for SSH events
- keyword searches for privileged execution (e.g., sudo)

## ISSO Interpretation
Logs provide accountability and support audit readiness by demonstrating:
- who accessed the system
- when access occurred
- whether privileged actions were performed
