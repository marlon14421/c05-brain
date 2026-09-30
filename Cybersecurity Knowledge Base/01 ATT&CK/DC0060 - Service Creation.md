---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0060"
source_url: "https://attack.mitre.org/datacomponents/DC0060"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0060: Service Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0060  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The registration of a new service or daemon on an operating system. *Data Collection Measures:* - Windows Event Logs - Event ID 4697 - Captures the creation of a new Windows service. - Event ID 7045 - Captures services installed by administrators or adversaries. - Event ID 7034 - Could indicate malicious service modification or exploitation. - Sysmon Logs - Sysmon Event ID 1 - Process Creation (captures service executables). - Sysmon Event ID 4 - Service state changes (detects service installation). - Sysmon Event ID 13 - Registry modifications (captures service persistence changes). - PowerShell Logging - Monitor `New-Service` and `Set-Service` PowerShell cmdlets in Event ID 4104 (Script Block Logging). - Linux/macOS Collection Methods - AuditD & Syslog Daemon Logs (`/var/log/syslog`, `/var/log/messages`, `/var/log/daemon.log`) - AuditD Rules: - `auditctl -w /etc/systemd/system -p wa -k service_creation` - Detects changes to `systemd` service configurations. - Systemd Journals (`journalctl -u `) - Captures newly created systemd services. - LaunchDaemons & LaunchAgents (macOS) - Monitor `/Library/LaunchDaemons/` and `/Library/LaunchAgents/` for new plist files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0060](https://attack.mitre.org/datacomponents/DC0060)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
