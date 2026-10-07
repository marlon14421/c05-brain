---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1053"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1053: AvosLocker — Defensive Application

## Source record

- [[01 ATT&CK/S1053 - AvosLocker|S1053 source record]]
- ATT&CK class: Malware
- Platforms: Linux, Windows
- Tactics: Not specified

## Source context

[AvosLocker](https://attack.mitre.org/software/S1053) is ransomware written in C++ that has been offered via the Ransomware-as-a-Service (RaaS) model. It was first observed in June 2021 and has been used against financial services, critical manufacturing, government facilities, and other critical infrastructure sectors in the United States. As of March 2022, [AvosLocker](https://attack.mitre.org/software/S1053) had also been used against organizations in Belgium, Canada, China, Germany, Saudi Arabia, Spain, Syria, Taiwan, Turkey, the United Arab Emirates, and the United Kingdom.(Citation: Malwarebytes AvosLocker Jul 2021)(Citation: Trend Micro AvosLocker Apr 2022)(Citation: Joint CSA AvosLocker Mar 2022)

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
