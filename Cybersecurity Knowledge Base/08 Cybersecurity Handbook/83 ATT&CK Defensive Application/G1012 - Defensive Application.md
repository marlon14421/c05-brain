---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1012"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1012: CURIUM — Defensive Application

## Source record

- [[01 ATT&CK/G1012 - CURIUM|G1012 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[CURIUM](https://attack.mitre.org/groups/G1012) is an Iranian threat group, first reported in September 2019 and active since at least July 2018, targeting IT service providers in the Middle East.(Citation: Symantec Tortoiseshell 2019) [CURIUM](https://attack.mitre.org/groups/G1012) has since invested in building relationships with potential targets via social media over a period of months to establish trust and confidence before sending malware. Security researchers note [CURIUM](https://attack.mitre.org/groups/G1012) has demonstrated great patience and persistence by chatting with potential targets daily and sending benign files to help lower their security consciousness.(Citation: Microsoft Iranian Threat Actor Trends November 2021)

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
