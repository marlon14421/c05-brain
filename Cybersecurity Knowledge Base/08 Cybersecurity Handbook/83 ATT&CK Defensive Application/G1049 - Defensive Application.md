---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1049"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1049: AppleJeus — Defensive Application

## Source record

- [[01 ATT&CK/G1049 - AppleJeus|G1049 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[AppleJeus](https://attack.mitre.org/groups/G1049) is a North Korean state-sponsored threat group attributed to the Reconnaissance General Bureau. Associated with the broader [Lazarus Group](https://attack.mitre.org/groups/G0032) umbrella of actors, [AppleJeus](https://attack.mitre.org/groups/G1049) has been active since at least 2018 and is closely aligned in resources with TEMP.hermit, another DPRK-affiliated group under the same umbrella.(Citation: dtex DPRK 2025 structure ITworkers) The group’s primary mission is to generate and launder revenue to provide financial support to the government. [AppleJeus](https://attack.mitre.org/groups/G1049) primarily targets the cryptocurrency industry and is most notably responsible for the [3CX Supply Chain Attack](https://attack.mitre.org/campaigns/C0057).(Citation: Mandiant 3cx UNC4736 2023) The group traditionally deploys malicious cryptocurrency software in combination with [Phishing](https://attack.mitre.org/techniques/T1566). From these compromised environments, it selectively deploys additional backdoors to enable extended operations against high-value financial targets.(Citation: Mandiant DPRK Groups 2023)(Citation: JPCert Blog Laz Subgroups 2025)

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
