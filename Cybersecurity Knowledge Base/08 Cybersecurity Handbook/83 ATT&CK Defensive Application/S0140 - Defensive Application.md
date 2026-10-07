---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0140"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0140: Shamoon — Defensive Application

## Source record

- [[01 ATT&CK/S0140 - Shamoon|S0140 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Shamoon](https://attack.mitre.org/software/S0140) is wiper malware that was first used by an Iranian group known as the "Cutting Sword of Justice" in 2012. Other versions known as Shamoon 2 and Shamoon 3 were observed in 2016 and 2018. [Shamoon](https://attack.mitre.org/software/S0140) has also been seen leveraging [RawDisk](https://attack.mitre.org/software/S0364) and Filerase to carry out data wiping tasks. Analysis has linked [Shamoon](https://attack.mitre.org/software/S0140) with [Kwampirs](https://attack.mitre.org/software/S0236) based on multiple shared artifacts and coding patterns.(Citation: Cylera Kwampirs 2022) The term Shamoon is sometimes used to refer to the group using the malware as well as the malware itself.(Citation: Palo Alto Shamoon Nov 2016)(Citation: Unit 42 Shamoon3 2018)(Citation: Symantec Shamoon 2012)(Citation: FireEye Shamoon Nov 2016)

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
