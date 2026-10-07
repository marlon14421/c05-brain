---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0531"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0531: Grandoreiro — Defensive Application

## Source record

- [[01 ATT&CK/S0531 - Grandoreiro|S0531 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Grandoreiro](https://attack.mitre.org/software/S0531) is a banking trojan written in Delphi that was first observed in 2016 and uses a Malware-as-a-Service (MaaS) business model. [Grandoreiro](https://attack.mitre.org/software/S0531) has confirmed victims in Brazil, Mexico, Portugal, and Spain.(Citation: Securelist Brazilian Banking Malware July 2020)(Citation: ESET Grandoreiro April 2020)

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
