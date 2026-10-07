---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1023"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1023: CreepyDrive — Defensive Application

## Source record

- [[01 ATT&CK/S1023 - CreepyDrive|S1023 source record]]
- ATT&CK class: Malware
- Platforms: Windows, Office Suite
- Tactics: Not specified

## Source context

[CreepyDrive](https://attack.mitre.org/software/S1023) is a custom implant has been used by [POLONIUM](https://attack.mitre.org/groups/G1005) since at least early 2022 for C2 with and exfiltration to actor-controlled OneDrive accounts.(Citation: Microsoft POLONIUM June 2022) [POLONIUM](https://attack.mitre.org/groups/G1005) has used a similar implant called CreepyBox that relies on actor-controlled DropBox accounts.(Citation: Microsoft POLONIUM June 2022)

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
