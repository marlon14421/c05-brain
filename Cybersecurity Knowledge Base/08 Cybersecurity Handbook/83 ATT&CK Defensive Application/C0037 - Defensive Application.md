---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0037"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0037: Water Curupira Pikabot Distribution — Defensive Application

## Source record

- [[01 ATT&CK/C0037 - Water Curupira Pikabot Distribution|C0037 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[Pikabot](https://attack.mitre.org/software/S1145) was distributed in [Water Curupira Pikabot Distribution](https://attack.mitre.org/campaigns/C0037) throughout 2023 by an entity linked to BlackBasta ransomware deployment via email attachments. This activity followed the take-down of [QakBot](https://attack.mitre.org/software/S0650), with several technical overlaps and similarities with [QakBot](https://attack.mitre.org/software/S0650), indicating a possible connection. The identified activity led to the deployment of tools such as [Cobalt Strike](https://attack.mitre.org/software/S0154), while coinciding with campaigns delivering [DarkGate](https://attack.mitre.org/software/S1111) and [IcedID](https://attack.mitre.org/software/S0483) en route to ransomware deployment.(Citation: TrendMicro Pikabot 2024)

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
