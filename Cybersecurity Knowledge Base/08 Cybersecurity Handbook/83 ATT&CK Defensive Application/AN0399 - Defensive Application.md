---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "AN0399"
attack_type: "Detection Analytic"
source: MITRE ATT&CK
---
# AN0399: Analytic 0399 — Defensive Application

## Source record

- [[01 ATT&CK/AN0399 - Analytic 0399|AN0399 source record]]
- ATT&CK class: Detection Analytic
- Platforms: Network Devices
- Tactics: Not specified

## Source context

Detects unauthorized or anomalous use of command-line interfaces (CLI) on network devices. Focuses on remote access sessions (e.g., SSH/Telnet), privilege escalation within CLI sessions, execution of high-risk commands (e.g., config replace, terminal monitor, no logging), and configuration changes outside of approved windows.

## Defensive focus

Treat the analytic as a hypothesis about observable behavior. Validate data availability, field meaning, time coverage, and environment-specific benign patterns before enabling response automation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Are required event sources enabled, retained, and correctly parsed for the relevant asset population?
- Does the analytic distinguish the behavior from common administrative and software activity?
- What benign test or sanitized dataset can validate the expected signal?
- What response action is proportionate, reversible, and approved?
- How will missed coverage, false positives, and rule changes be measured?

## Safe validation

Test against synthetic events or sanitized, authorized data. Do not trigger suspicious behavior on third-party or production systems simply to produce an alert. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
