---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1246"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1246: BeaverTail — Defensive Application

## Source record

- [[01 ATT&CK/S1246 - BeaverTail|S1246 source record]]
- ATT&CK class: Malware
- Platforms: Linux, macOS, Windows
- Tactics: Not specified

## Source context

[BeaverTail](https://attack.mitre.org/software/S1246) is a malware that has both a JavaScript and C++ variant. Active since 2022, [BeaverTail](https://attack.mitre.org/software/S1246) is capable of stealing logins from browsers and serves as a downloader for second stage payloads. [BeaverTail](https://attack.mitre.org/software/S1246) has previously been leveraged by North Korea-affiliated actors identified as DeceptiveDevelopment or [Contagious Interview](https://attack.mitre.org/groups/G1052). [BeaverTail](https://attack.mitre.org/software/S1246) has been delivered to victims through code repository sites and has been embedded within malicious attachments.(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)

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
