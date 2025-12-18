# SIEM Setup and Log Analysis

## Tool Used
Splunk Enterprise SIEM

## Log Ingestion
Configured Splunk to ingest local Windows Event Logs:
- Security
- Application
- System

Log ingestion was configured manually using inputs.conf.

## Detection
Performed searches to identify:
- Successful logins (Event ID 4624)
- Failed login attempts (Event ID 4625)

## Outcome
Confirmed that simulated activity generated detectable events within the SIEM.
