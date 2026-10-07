---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1010"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1010: VPNFilter — Defensive Application

## Source record

- [[01 ATT&CK/S1010 - VPNFilter|S1010 source record]]
- ATT&CK class: Malware
- Platforms: Network Devices, Linux
- Tactics: Not specified

## Source context

[VPNFilter](https://attack.mitre.org/software/S1010) is a multi-stage, modular platform with versatile capabilities to support both intelligence-collection and destructive cyber attack operations. [VPNFilter](https://attack.mitre.org/software/S1010) modules such as its packet sniffer ('ps') can collect traffic that passes through an infected device, allowing the theft of website credentials and monitoring of Modbus SCADA protocols. (Citation: William Largent June 2018) (Citation: Carl Hurd March 2019) [VPNFilter](https://attack.mitre.org/software/S1010) was assessed to be replaced by [Sandworm Team](https://attack.mitre.org/groups/G0034) with [Cyclops Blink](https://attack.mitre.org/software/S0687) starting in 2019.(Citation: NCSC CISA Cyclops Blink Advisory February 2022)

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
