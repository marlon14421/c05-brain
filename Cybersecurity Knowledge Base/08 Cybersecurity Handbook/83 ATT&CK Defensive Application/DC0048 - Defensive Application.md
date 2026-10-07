---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0048"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0048: Named Pipe Metadata — Defensive Application

## Source record

- [[01 ATT&CK/DC0048 - Named Pipe Metadata|DC0048 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Contextual data about a named pipe on a system, including pipe name and creating process (ex: Sysmon EIDs 17-18) *Data Collection Measures:* - Windows: - Sysmon Event ID 17: Logs the creation of a named pipe. - Sysmon Event ID 18: Logs connection attempts to a named pipe. - Windows Security Event ID 5145: Logs access attempts to named pipes via SMB shares. - ETW (Event Tracing for Windows): Provides deep telemetry into named pipe interactions. - Linux/macOS: - AuditD (`mkfifo`, `open`, `read`, `write` syscalls): Tracks FIFO (named pipe) creation and usage. - Lsof (`lsof -p ` or `lsof | grep PIPE`): Lists active named pipes and associated processes. - Strace (`strace -e open `): Monitors named pipe interactions. - Endpoint Detection & Response (EDR): - Capture named pipe events as part of process tracking. - Memory Forensics: - Volatility Plugin (`pipescan`): Enumerates named pipes in system memory. - Rekall Framework: Identifies active named pipes and associated processes.

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
