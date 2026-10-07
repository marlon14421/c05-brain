---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9041"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9041: TeamPCP Cloud Stealer — Defensive Application

## Source record

- [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041 source record]]
- ATT&CK class: Malware
- Platforms: Containers, Linux, macOS, SaaS, Windows
- Tactics: Not specified

## Source context

The [TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) is a comprehensive filesystem credential stealer that can harvest, encrypt, and exfiltrate credentials from over 50 sensitive file paths across CI/CD, cloud, developer tooling, and container environments. The [TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) was the primary payload used by [TeamPCP](https://attack.mitre.org/groups/G1056) in March 2026 during early stages of a cascading supply chain campaign targeting CI/CD workflows.(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Sysdig TeamPCP MAR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Google AI Threat Tracker MAY 2026)(Citation: FBI TeamPCP JUL 2026)

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
