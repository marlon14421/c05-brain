---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "AN0692"
attack_type: "Detection Analytic"
source: MITRE ATT&CK
---
# AN0692: Analytic 0692 — Defensive Application

## Source record

- [[01 ATT&CK/AN0692 - Analytic 0692|AN0692 source record]]
- ATT&CK class: Detection Analytic
- Platforms: Windows
- Tactics: Not specified

## Source context

IAAS (Cloud images/VMs): A new VM/instance is launched from a non-approved or newly-seen image (AMI/GCP Image/Azure Image). On first boot, cloud-init/user-data or embedded agents download code, spawn system utilities, or open outbound C2/mining traffic. The analytic correlates Instance/Image Creation → Instance Start → in-guest Process/Command Execution and/or anomalous network traffic.

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
