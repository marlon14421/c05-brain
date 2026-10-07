---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G0090"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G0090: WIRTE — Defensive Application

## Source record

- [[01 ATT&CK/G0090 - WIRTE|G0090 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[WIRTE](https://attack.mitre.org/groups/G0090) is a cyberespionage actor, believed to be a subgroup of the Hamas-affiliated Gaza Cybergang, that has been active since at least August 2018. [WIRTE](https://attack.mitre.org/groups/G0090) has targeted diplomatic, financial, military, legal, and technology organizations across the Middle East, North Africa, and in Europe to gather intelligence. [WIRTE](https://attack.mitre.org/groups/G0090) has remained persistently active despite the ongoing Israel-Hamas conflict and has expanded their operations to include wiper malware attacks against Israeli targets.(Citation: Lab52 WIRTE Apr 2019)(Citation: Kaspersky WIRTE November 2021)(Citation: Check Point Wirte NOV 2024)(Citation: Palo Alto Ashen Lepus DEC 2025)

## Defensive focus

Use the record as contextual threat intelligence, not as attribution evidence or proof that a specific organization is targeted. Prioritize observable behaviors and relevant defensive exposure.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which source claims are independently supported, current, and relevant to this environment?
- Which behavior, platform, or dependency can be translated into a control or detection hypothesis?
- Are names, indicators, and reported relationships time-bounded and subject to reuse or reclassification?
- What local evidence would confirm or disconfirm the hypothesis?
- Which response steps protect evidence and avoid premature attribution?

## Safe validation

Use public reporting and sanitized lab data. Do not acquire or execute malware or tools from a catalog entry; use approved analysis procedures and isolated environments when necessary. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
