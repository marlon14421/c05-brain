---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1138"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1138: Gootloader — Defensive Application

## Source record

- [[01 ATT&CK/S1138 - Gootloader|S1138 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Gootloader](https://attack.mitre.org/software/S1138) is a Javascript-based infection framework that has been used since at least 2020 as a delivery method for the Gootkit banking trojan, [Cobalt Strike](https://attack.mitre.org/software/S0154), [REvil](https://attack.mitre.org/software/S0496), and others. [Gootloader](https://attack.mitre.org/software/S1138) operates on an "Initial Access as a Service" model and has leveraged [SEO Poisoning](https://attack.mitre.org/techniques/T1608/006) to provide access to entities in multiple sectors worldwide including financial, military, automotive, pharmaceutical, and energy.(Citation: Sophos Gootloader)(Citation: SentinelOne Gootloader June 2021)

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
