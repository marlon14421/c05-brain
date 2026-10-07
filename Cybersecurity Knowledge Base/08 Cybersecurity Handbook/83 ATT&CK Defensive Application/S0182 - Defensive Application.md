---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0182"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0182: FinFisher — Defensive Application

## Source record

- [[01 ATT&CK/S0182 - FinFisher|S0182 source record]]
- ATT&CK class: Malware
- Platforms: Windows, Android
- Tactics: Not specified

## Source context

[FinFisher](https://attack.mitre.org/software/S0182) is a government-grade commercial surveillance spyware reportedly sold exclusively to government agencies for use in targeted and lawful criminal investigations. It is heavily obfuscated and uses multiple anti-analysis techniques. It has other variants including [Wingbird](https://attack.mitre.org/software/S0176). (Citation: FinFisher Citation) (Citation: Microsoft SIR Vol 21) (Citation: FireEye FinSpy Sept 2017) (Citation: Securelist BlackOasis Oct 2017) (Citation: Microsoft FinFisher March 2018)

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
