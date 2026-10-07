---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1056"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1056: TeamPCP — Defensive Application

## Source record

- [[01 ATT&CK/G1056 - TeamPCP|G1056 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[TeamPCP](https://attack.mitre.org/groups/G1056) is a financially-motivated, cloud-native threat group that has been active since at least September 2025. Initially focused on ransomware and cryptocurrency theft, [TeamPCP](https://attack.mitre.org/groups/G1056) shifted in early 2026 to systematic, worm-driven credential theft and software supply chain attacks targeting Continuous Integration and Continuous Delivery (CI/CD) workflows. [TeamPCP](https://attack.mitre.org/groups/G1056) has monetized access through extortion and through partnerships with ransomware actors including Vect and CipherForce.(Citation: Wiz TeamPCP Profile MAY 2026)(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Trend Micro TeamPCP MAY 2026)

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
