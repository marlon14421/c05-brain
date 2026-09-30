---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0018"
source_url: "https://attack.mitre.org/datacomponents/DC0018"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0018: Host Status

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0018  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Logging, messaging, and other artifacts that highlight the health and operational state of host-based security sensors, such as Endpoint Detection and Response (EDR) agents, antivirus software, logging services, and system monitoring tools. Monitoring sensor health is essential for detecting misconfigurations, sensor failures, tampering, or deliberate security control evasion by adversaries. *Data Collection Measures:* - Windows Event Logs: - Event ID 1074 (System Shutdown): Detects unexpected system reboots/shutdowns. - Event ID 6006 (Event Log Stopped): Logs when Windows event logging is stopped. - Event ID 16 (Sysmon): Detects configuration state changes that may indicate log tampering. - Event ID 12 (Windows Defender Status Change) – Detects changes in Windows Defender state. - Linux/macOS Monitoring: - `/var/log/syslog`, `/var/log/auth.log`, `/var/log/kern.log` - Journald (journalctl) for kernel and system alerts. - Endpoint Detection and Response (EDR) Tools: - Monitor agent health status, detect sensor tampering, and alert on missing telemetry. - Mobile Threat Intelligence Logs: - Samsung Knox, SafetyNet, iOS Secure Enclave provide sensor health status for mobile endpoints.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0018](https://attack.mitre.org/datacomponents/DC0018)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
