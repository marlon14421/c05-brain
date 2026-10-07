---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0038"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0038: HomeLand Justice — Defensive Application

## Source record

- [[01 ATT&CK/C0038 - HomeLand Justice|C0038 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[HomeLand Justice](https://attack.mitre.org/campaigns/C0038) was a disruptive cyber campaign conducted by Iranian state-affiliated actors against Albanian government networks in July and September 2022. The activity combined ransomware, wiper malware, and data leak operations. Initial access for [HomeLand Justice](https://attack.mitre.org/campaigns/C0038) was established as early as May 2021, and threat actors moved laterally, exfiltrated sensitive information, and maintained persistence for approximately 14 months prior to the destructive phase of the operation. Responsibility was claimed by the "HomeLand Justice" front, which framed the campaign as retaliation against the Mujahedeen-e Khalq (MEK), an Iranian opposition group with a presence in Albania. Multiple Iran-nexus groups are assessed to have participated in the campaign, including [HEXANE](https://attack.mitre.org/groups/G1001) who probed victim infrastructure.(Citation: Mandiant ROADSWEEP August 2022)(Citation: Microsoft Albanian Government Attacks September 2022)(Citation: CISA Iran Albanian Attacks September 2022) A second wave of attacks was launched in September 2022 using similar tactics following public attribution of the previous activity to Iran and the severing of diplomatic ties between Iran and Albania.(Citation: CISA Iran Albanian Attacks September 2022)

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
