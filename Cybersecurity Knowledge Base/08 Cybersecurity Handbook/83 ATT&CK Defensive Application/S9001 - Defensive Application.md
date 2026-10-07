---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9001"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9001: SystemBC — Defensive Application

## Source record

- [[01 ATT&CK/S9001 - SystemBC|S9001 source record]]
- ATT&CK class: Malware
- Platforms: Linux, Windows
- Tactics: Not specified

## Source context

[SystemBC](https://attack.mitre.org/software/S9001) is a malware family offered as a malware-as-a-service (MaaS) that is used to establish command and control and facilitate follow-on activity, including ransomware deployment.[SystemBC](https://attack.mitre.org/software/S9001) executes a variety of tasks including setting up SOCKS5 proxies, maintaining persistence, ingesting malicious files, and handing C2 communication. [SystemBC](https://attack.mitre.org/software/S9001) was first detected in 2018, and has been used by [Wizard Spider](https://attack.mitre.org/groups/G0102) since at least 2020, and by [FIN7](https://attack.mitre.org/groups/G0046) since at least 2022.(Citation: TrumanKroll_SYSTEMBCServer_Jan2024)(Citation: SophosGnGal_SystemBC_Dec2020)(Citation: BlackBasta)(Citation: AhnLab_SystemBC_Apr2022)(Citation: Lumen_SystemBC_Sept2025)

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
