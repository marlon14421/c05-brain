---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1073"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1073: Royal — Defensive Application

## Source record

- [[01 ATT&CK/S1073 - Royal|S1073 source record]]
- ATT&CK class: Malware
- Platforms: Windows, ESXi
- Tactics: Not specified

## Source context

[Royal](https://attack.mitre.org/software/S1073) is ransomware that first appeared in early 2022; a version that also targets ESXi servers was later observed in February 2023. [Royal](https://attack.mitre.org/software/S1073) employs partial encryption and multiple threads to evade detection and speed encryption. [Royal](https://attack.mitre.org/software/S1073) has been used in attacks against multiple industries worldwide--including critical infrastructure. Security researchers have identified similarities in the encryption routines and TTPs used in [Royal](https://attack.mitre.org/software/S1073) and [Conti](https://attack.mitre.org/software/S0575) attacks and noted a possible connection between their operators.(Citation: Microsoft Royal ransomware November 2022)(Citation: Cybereason Royal December 2022)(Citation: Kroll Royal Deep Dive February 2023)(Citation: Trend Micro Royal Linux ESXi February 2023)(Citation: CISA Royal AA23-061A March 2023)

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
