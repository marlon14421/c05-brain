---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0035"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0035: Process Access — Defensive Application

## Source record

- [[01 ATT&CK/DC0035 - Process Access|DC0035 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Refers to an event where one process attempts to open another process, typically to inspect or manipulate its memory, access handles, or modify execution flow. Monitoring these access attempts can provide valuable insight into both benign and malicious behaviors, such as debugging, inter-process communication (IPC), or process injection. *Data Collection Measures:* - Endpoint Detection and Response (EDR) Tools: - EDR solutions that provide telemetry on inter-process access and memory manipulation. - Sysmon (Windows): - Event ID 10: Captures process access attempts, including: - Source process (initiator) - Target process (victim) - Access rights requested - Process ID correlation - Windows Event Logs: - Event ID 4656 (Audit Handle to an Object): Logs access attempts to system objects. - Event ID 4690 (Attempted Process Modification): Can help identify unauthorized process changes. - Linux/macOS Monitoring: - AuditD: Monitors process access through syscall tracing (e.g., `ptrace`, `open`, `read`, `write`). - eBPF/XDP: Used for low-level monitoring of kernel process access. - OSQuery: Query process access behavior via structured SQL-like logging. - Procmon (Process Monitor) and Debugging Tools: - Windows Procmon: Captures real-time process interactions. - Linux strace / ptrace: Useful for tracking process behavior at the system call level.

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
