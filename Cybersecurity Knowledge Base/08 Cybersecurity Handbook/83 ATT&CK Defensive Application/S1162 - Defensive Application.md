---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1162"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1162: Playcrypt — Defensive Application

## Source record

- [[01 ATT&CK/S1162 - Playcrypt|S1162 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Playcrypt](https://attack.mitre.org/software/S1162) is a ransomware that has been used by [Play](https://attack.mitre.org/groups/G1040) since at least 2022 in attacks against against the business, government, critical infrastructure, healthcare, and media sectors in North America, South America, and Europe. [Playcrypt](https://attack.mitre.org/software/S1162) derives its name from adding the .play extension to encrypted files and has overlap with tactics and tools associated with Hive and Nokoyawa ransomware and infrastructure associated with Quantum ransomware.(Citation: Microsoft PlayCrypt August 2022)(Citation: CISA Play Ransomware Advisory December 2023)(Citation: Trend Micro Ransomware Spotlight Play July 2023)

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
