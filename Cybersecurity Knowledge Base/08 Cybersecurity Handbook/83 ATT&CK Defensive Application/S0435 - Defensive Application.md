---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0435"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0435: PLEAD — Defensive Application

## Source record

- [[01 ATT&CK/S0435 - PLEAD|S0435 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[PLEAD](https://attack.mitre.org/software/S0435) is a remote access tool (RAT) and downloader used by [BlackTech](https://attack.mitre.org/groups/G0098) in targeted attacks in East Asia including Taiwan, Japan, and Hong Kong.(Citation: TrendMicro BlackTech June 2017)(Citation: JPCert PLEAD Downloader June 2018) [PLEAD](https://attack.mitre.org/software/S0435) has also been referred to as [TSCookie](https://attack.mitre.org/software/S0436), though more recent reporting indicates likely separation between the two. [PLEAD](https://attack.mitre.org/software/S0435) was observed in use as early as March 2017.(Citation: JPCert TSCookie March 2018)(Citation: JPCert PLEAD Downloader June 2018)

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
