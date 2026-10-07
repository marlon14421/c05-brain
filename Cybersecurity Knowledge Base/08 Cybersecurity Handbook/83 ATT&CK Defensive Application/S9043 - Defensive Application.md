---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9043"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9043: Mini Shai-Hulud — Defensive Application

## Source record

- [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043 source record]]
- ATT&CK class: Malware
- Platforms: Containers, IaaS, Linux, macOS, SaaS, Windows
- Tactics: Not specified

## Source context

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) is a credential stealer and self-replicating supply chain worm, derived from [Shai-Hulud](https://attack.mitre.org/software/S9008), that has been used by [TeamPCP](https://attack.mitre.org/groups/G1056) to target Continuous Integration and Continuous Delivery/Deployment (CI/CD) workflows since at least 2026. [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) can compromise credentials across multiple cloud, container, and AI configuration file paths and can use stolen npm and GitHub OIDC tokens to spread to other packages maintained by the compromised user. [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) also has a targeted wiper component and has used multiple C2 and data exfiltration mechanisms.(Citation: Wiz Mini Shai-Hulud MAY 2026)(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)(Citation: FBI TeamPCP JUL 2026)

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
