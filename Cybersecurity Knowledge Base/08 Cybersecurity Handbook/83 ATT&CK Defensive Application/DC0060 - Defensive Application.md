---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0060"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0060: Service Creation — Defensive Application

## Source record

- [[01 ATT&CK/DC0060 - Service Creation|DC0060 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The registration of a new service or daemon on an operating system. *Data Collection Measures:* - Windows Event Logs - Event ID 4697 - Captures the creation of a new Windows service. - Event ID 7045 - Captures services installed by administrators or adversaries. - Event ID 7034 - Could indicate malicious service modification or exploitation. - Sysmon Logs - Sysmon Event ID 1 - Process Creation (captures service executables). - Sysmon Event ID 4 - Service state changes (detects service installation). - Sysmon Event ID 13 - Registry modifications (captures service persistence changes). - PowerShell Logging - Monitor `New-Service` and `Set-Service` PowerShell cmdlets in Event ID 4104 (Script Block Logging). - Linux/macOS Collection Methods - AuditD & Syslog Daemon Logs (`/var/log/syslog`, `/var/log/messages`, `/var/log/daemon.log`) - AuditD Rules: - `auditctl -w /etc/systemd/system -p wa -k service_creation` - Detects changes to `systemd` service configurations. - Systemd Journals (`journalctl -u `) - Captures newly created systemd services. - LaunchDaemons & LaunchAgents (macOS) - Monitor `/Library/LaunchDaemons/` and `/Library/LaunchAgents/` for new plist files.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
