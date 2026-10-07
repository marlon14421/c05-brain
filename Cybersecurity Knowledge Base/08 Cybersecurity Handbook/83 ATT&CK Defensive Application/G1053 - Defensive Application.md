---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1053"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1053: Storm-0501 — Defensive Application

## Source record

- [[01 ATT&CK/G1053 - Storm-0501|G1053 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[Storm-0501](https://attack.mitre.org/groups/G1053) is a financially motivated cyber criminal group that uses commodity and open-source tools to conduct ransomware operations. [Storm-0501](https://attack.mitre.org/groups/G1053) has been active since 2021 and has previously been affiliated with Sabbath Ransomware and other Ransomware-as-a-Service (RaaS) variants such as Hive, [BlackCat](https://attack.mitre.org/software/S1068), Hunters International, [LockBit 3.0](https://attack.mitre.org/software/S1202), and [Embargo](https://attack.mitre.org/software/S1247) ransomware.(Citation: Avertium Storm-0501 Sabbath Ransomware Arcane January 2022)(Citation: Microsoft Storm-501 Sabbath Ransomware Embargo September 2024)(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)(Citation: Google Mandiant Storm-0501 Sabbath Ransomware November 2021)

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
