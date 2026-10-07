---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9002"
attack_type: "Tool"
source: MITRE ATT&CK
---
# S9002: Diskpart — Defensive Application

## Source record

- [[01 ATT&CK/S9002 - Diskpart|S9002 source record]]
- ATT&CK class: Tool
- Platforms: Windows
- Tactics: Not specified

## Source context

[Diskpart](https://attack.mitre.org/software/S9002) is a Windows command-line utility that is used to manage the computer’s drives, which includes disks, partitions, volumes and virtual hard disks.(Citation: Microsoft_diskpart_Feb2023) Adversaries may abuse [Diskpart](https://attack.mitre.org/software/S9002) to perform discovery and destructive actions on a system’s storage. For example, adversaries have been observed using [Diskpart](https://attack.mitre.org/software/S9002) to conduct [Discovery](https://attack.mitre.org/tactics/TA0007) techniques to enumerate disks and volumes to gather information about the host environment, and to execute commands such as `clean all` to remove partition information and overwrite data across disks, resulting in data destruction.(Citation: Trendmicro_RansomHub_Dec2024)

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
