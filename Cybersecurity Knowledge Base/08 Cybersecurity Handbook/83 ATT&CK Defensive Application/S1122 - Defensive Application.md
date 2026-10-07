---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1122"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1122: Mispadu — Defensive Application

## Source record

- [[01 ATT&CK/S1122 - Mispadu|S1122 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Mispadu](https://attack.mitre.org/software/S1122) is a banking trojan written in Delphi that was first observed in 2019 and uses a Malware-as-a-Service (MaaS) business model.(Citation: ESET Security Mispadu Facebook Ads 2019)(Citation: SCILabs Malteiro 2021) This malware is operated, managed, and sold by the [Malteiro](https://attack.mitre.org/groups/G1026) cybercriminal group.(Citation: SCILabs Malteiro 2021) [Mispadu](https://attack.mitre.org/software/S1122) has mainly been used to target victims in Brazil and Mexico, and has also had confirmed operations throughout Latin America and Europe.(Citation: SCILabs Malteiro 2021)(Citation: SCILabs URSA/Mispadu Evolution 2023)(Citation: Segurança Informática URSA Sophisticated Loader 2020)

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
