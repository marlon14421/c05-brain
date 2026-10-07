---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1054"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1054: MirrorFace — Defensive Application

## Source record

- [[01 ATT&CK/G1054 - MirrorFace|G1054 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[MirrorFace](https://attack.mitre.org/groups/G1054) is a People's Republic of China (PRC)-aligned cyberespionage actor believed to be a subgroup under the [menuPass](https://attack.mitre.org/groups/G0045) umbrella based on targeting, tools, and infrastructure overlaps. [MirrorFace](https://attack.mitre.org/groups/G1054) has been active since at least 2019, at first exclusively targeting Japanese organizations across the media, defense, diplomatic, financial, manufacturing, and academic sectors. Subsequent [MirrorFace](https://attack.mitre.org/groups/G1054) operations included targets in Central Europe and featured use of [LODEINFO](https://attack.mitre.org/software/S9020), [HiddenFace](https://attack.mitre.org/software/S9023), and [UPPERCUT](https://attack.mitre.org/software/S0275) malware.(Citation: Kaspersky LODEINFO OCT 2022)(Citation: Kaspersky LODEINFO Part II OCT 2022)(Citation: ESET MirrorFace DEC 2022)(Citation: JPCERT MirrorFace JUL 2024)(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: Trend Micro Earth Kasha Updates APR 2025)

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
