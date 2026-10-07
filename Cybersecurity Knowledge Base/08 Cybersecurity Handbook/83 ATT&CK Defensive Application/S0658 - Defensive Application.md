---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0658"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0658: XCSSET — Defensive Application

## Source record

- [[01 ATT&CK/S0658 - XCSSET|S0658 source record]]
- ATT&CK class: Malware
- Platforms: macOS
- Tactics: Not specified

## Source context

[XCSSET](https://attack.mitre.org/software/S0658) is a modular macOS malware family delivered through infected Xcode projects and executed when the project is compiled. Active since August 2020, it has been observed installing backdoors, spoofed browsers, collecting data, and encrypting user files. It is composed of SHC-compiled shell scripts and run-only AppleScripts, often hiding in apps that mimic system tools (such as Xcode, Mail, or Notes) or use familiar icons (like Launchpad) to avoid detection.(Citation: trendmicro xcsset xcode project 2020)(Citation: April 2021 TrendMicro XCSSET)(Citation: Microsoft March 2025 XCSSET)

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
