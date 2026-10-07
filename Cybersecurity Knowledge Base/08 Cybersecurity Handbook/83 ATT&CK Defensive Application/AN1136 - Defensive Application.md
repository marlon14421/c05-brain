---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "AN1136"
attack_type: "Detection Analytic"
source: MITRE ATT&CK
---
# AN1136: Analytic 1136 — Defensive Application

## Source record

- [[01 ATT&CK/AN1136 - Analytic 1136|AN1136 source record]]
- ATT&CK class: Detection Analytic
- Platforms: macOS
- Tactics: Not specified

## Source context

Abuse of extended attributes (xattrs) to hide payloads in com.apple.* or custom keys. Defender perspective: monitor suspicious use of xattr command with -w (write) and -p (print) flags, especially when followed by execution of interpreters like bash, Python, or osascript. Behavior chain includes: (1) suspicious file modification with new com.apple.* attributes, (2) attribute content inconsistent with expected metadata tags (e.g., high entropy), (3) subsequent process execution correlated with extraction of the attribute.

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
