---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1130"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1130: Raspberry Robin — Defensive Application

## Source record

- [[01 ATT&CK/S1130 - Raspberry Robin|S1130 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Raspberry Robin](https://attack.mitre.org/software/S1130) is initial access malware first identified in September 2021, and active through early 2024. The malware is notable for spreading via infected USB devices containing a malicious LNK object that, on execution, retrieves remote hosted payloads for installation. [Raspberry Robin](https://attack.mitre.org/software/S1130) has been widely used against various industries and geographies, and as a precursor to information stealer, ransomware, and other payloads such as [SocGholish](https://attack.mitre.org/software/S1124), [Cobalt Strike](https://attack.mitre.org/software/S0154), [IcedID](https://attack.mitre.org/software/S0483), and [Bumblebee](https://attack.mitre.org/software/S1039).(Citation: TrendMicro RaspberryRobin 2022)(Citation: RedCanary RaspberryRobin 2022)(Citation: HP RaspberryRobin 2024) The DLL componenet in the [Raspberry Robin](https://attack.mitre.org/software/S1130) infection chain is also referred to as "Roshtyak."(Citation: Avast RaspberryRobin 2022) The name "Raspberry Robin" is used to refer to both the malware as well as the threat actor associated with its use, although the Raspberry Robin operators are also tracked as Storm-0856 by some vendors.(Citation: Microsoft RaspberryRobin 2022)

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
