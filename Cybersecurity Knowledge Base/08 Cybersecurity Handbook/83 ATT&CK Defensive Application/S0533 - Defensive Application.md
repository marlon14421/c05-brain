---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0533"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0533: SLOTHFULMEDIA — Defensive Application

## Source record

- [[01 ATT&CK/S0533 - SLOTHFULMEDIA|S0533 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) is a remote access Trojan written in C++ that has been used by an unidentified "sophisticated cyber actor" since at least January 2017.(Citation: CISA MAR SLOTHFULMEDIA October 2020)(Citation: Costin Raiu IAmTheKing October 2020) It has been used to target government organizations, defense contractors, universities, and energy companies in Russia, India, Kazakhstan, Kyrgyzstan, Malaysia, Ukraine, and Eastern Europe.(Citation: USCYBERCOM SLOTHFULMEDIA October 2020)(Citation: Kaspersky IAmTheKing October 2020) In October 2020, Kaspersky Labs assessed [SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) is part of an activity cluster it refers to as "IAmTheKing".(Citation: Kaspersky IAmTheKing October 2020) ESET also noted code similarity between [SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) and droppers used by a group it refers to as "PowerPool".(Citation: ESET PowerPool Code October 2020)

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
