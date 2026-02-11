\# Phase 2 – Windows Event Logging (Baseline)



\## Objective

Establish familiarity with Windows Security Event Logs to support auditing, monitoring, and compliance activities aligned with ISSO responsibilities.



---



\## Environment

\- Windows 10 / Windows 11 workstation

\- Event Viewer (eventvwr.msc)

\- Local Administrator access



---



\## Logs Reviewed

\- Security

\- System

\- Application



Primary focus was placed on the \*\*Security\*\* log due to its relevance to authentication, authorization, and audit requirements.



---



\## Key Security Events Observed



\### Logon / Authentication Events

\- Successful logons (Event ID 4624)

\- Failed logon attempts (Event ID 4625)



These events demonstrate how Windows records authentication activity and supports account monitoring and incident review.



---



\### Account and Privilege Activity

\- User account changes

\- Privilege use events



These logs are critical for identifying unauthorized access attempts and validating least-privilege enforcement.



---



\## Observations

\- Security logs provide detailed, timestamped records suitable for auditing and investigations.

\- Event IDs allow quick identification of specific security-relevant actions.

\- Logs support traceability and accountability requirements found in compliance frameworks.



---



\## ISSO Relevance

Windows Event Logs support:

\- Audit logging and review

\- Incident detection and investigation

\- Compliance with NIST 800-53 audit and accountability controls

\- Evidence collection for security assessments



---



\## Next Steps

\- Correlate Windows events with Linux and network-based logs

\- Identify events relevant to baseline vs anomalous behavior

\- Map observed events to compliance control requirements



