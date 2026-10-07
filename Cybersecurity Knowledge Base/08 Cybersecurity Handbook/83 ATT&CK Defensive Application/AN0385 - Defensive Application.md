---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "AN0385"
attack_type: "Detection Analytic"
source: MITRE ATT&CK
---
# AN0385: Analytic 0385 — Defensive Application

## Source record

- [[01 ATT&CK/AN0385 - Analytic 0385|AN0385 source record]]
- ATT&CK class: Detection Analytic
- Platforms: Linux
- Tactics: Not specified

## Source context

Processes invoking destructive commands (dd, shred, wipe) with raw device targets (e.g., /dev/sda, /dev/nvme0n1). Detect direct writes to disk partitions and abnormal superblock or bootloader modifications. Correlate shell execution with subsequent block device I/O.

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
