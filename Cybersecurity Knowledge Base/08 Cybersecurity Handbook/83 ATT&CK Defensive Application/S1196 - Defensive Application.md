---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1196"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1196: Troll Stealer — Defensive Application

## Source record

- [[01 ATT&CK/S1196 - Troll Stealer|S1196 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Troll Stealer](https://attack.mitre.org/software/S1196) is an information stealer written in Go associated with [Kimsuky](https://attack.mitre.org/groups/G0094) operations. [Troll Stealer](https://attack.mitre.org/software/S1196) has typically been delivered through a dropper disguised as a legitimate security program installation file. [Troll Stealer](https://attack.mitre.org/software/S1196) features code similar to [AppleSeed](https://attack.mitre.org/software/S0622), also uniquely associated with [Kimsuky](https://attack.mitre.org/groups/G0094) operations.(Citation: S2W Troll Stealer 2024)(Citation: Symantec Troll Stealer 2024)

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
