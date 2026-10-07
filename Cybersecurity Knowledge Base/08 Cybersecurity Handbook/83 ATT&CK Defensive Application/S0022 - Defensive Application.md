---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0022"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0022: Uroburos — Defensive Application

## Source record

- [[01 ATT&CK/S0022 - Uroburos|S0022 source record]]
- ATT&CK class: Malware
- Platforms: Linux, Windows, macOS
- Tactics: Not specified

## Source context

[Uroburos](https://attack.mitre.org/software/S0022) is a sophisticated cyber espionage tool written in C that has been used by units within Russia's Federal Security Service (FSB) associated with the [Turla](https://attack.mitre.org/groups/G0010) toolset to collect intelligence on sensitive targets worldwide. [Uroburos](https://attack.mitre.org/software/S0022) has several variants and has undergone nearly constant upgrade since its initial development in 2003 to keep it viable after public disclosures. [Uroburos](https://attack.mitre.org/software/S0022) is typically deployed to external-facing nodes on a targeted network and has the ability to leverage additional tools and TTPs to further exploit an internal network. [Uroburos](https://attack.mitre.org/software/S0022) has interoperable implants for Windows, Linux, and macOS, employs a high level of stealth in communications and architecture, and can easily incorporate new or replacement components.(Citation: Joint Cybersecurity Advisory AA23-129A Snake Malware May 2023)(Citation: Kaspersky Turla)

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
