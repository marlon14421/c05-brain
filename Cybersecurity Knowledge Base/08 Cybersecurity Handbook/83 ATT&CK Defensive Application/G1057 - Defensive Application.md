---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1057"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1057: ShinyHunters — Defensive Application

## Source record

- [[01 ATT&CK/G1057 - ShinyHunters|G1057 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[ShinyHunters](https://attack.mitre.org/groups/G1057) is a cyber criminal collective that has been active since at least 2019 operating under the ShinyCorp persona. [ShinyHunters](https://attack.mitre.org/groups/G1057) has targeted multiple industries and geographic regions gathering legitimate credentials and personally identifiable information (PII) for resale or extortion of victims. [ShinyHunters](https://attack.mitre.org/groups/G1057) has been associated with the broader collective called The Community, also known as The Com whose members have also included [Scattered Spider](https://attack.mitre.org/groups/G1015) and [LAPSUS$](https://attack.mitre.org/groups/G1004). Public reporting has mentioned a variety of names for operations [ShinyHunters](https://attack.mitre.org/groups/G1057) members have reportedly conducted with members of other groups, including “Scattered Lapsus Hunters,” “Scattered Lapsus Shiny Hunters,” and “SLSH.”(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)(Citation: SOCRadar_ShinyHunters_Mar2024)(Citation: Unit42KelleyVaya_BlingLibra_Aug2024)(Citation: Intel471_SH_Aug2021)(Citation: FBI_SHLMS_May2026)(Citation: Google_SHOracle_Jun2026)(Citation: Mandiant_SHDataTheft_Jan2026)(Citation: Google Salesforce JUN 2025)

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
