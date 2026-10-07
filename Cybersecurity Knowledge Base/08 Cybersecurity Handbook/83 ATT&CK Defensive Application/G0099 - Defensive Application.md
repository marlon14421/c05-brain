---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G0099"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G0099: APT-C-36 — Defensive Application

## Source record

- [[01 ATT&CK/G0099 - APT-C-36|G0099 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[APT-C-36](https://attack.mitre.org/groups/G0099) is a suspected South American threat group that has engaged in espionage and financially motivated operations since at least 2018. [APT-C-36](https://attack.mitre.org/groups/G0099) has targeted government institutions and entities in the financial, energy, and professional manufacturing sectors across Colombia and other Latin American countries.(Citation: QiAnXin APT-C-36 Feb2019)(Citation: Kaspersky BlindEagle AUG 2024)(Citation: Check Point Blind Eagle MAR 2025)(Citation: Recorded Future TAG-144 AUG 2025)

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
