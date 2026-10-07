---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0063"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0063: 2025 Poland Wiper Attacks — Defensive Application

## Source record

- [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063) is a Russian state-sponsored campaign that conducted destructive cyberattacks against Polish energy infrastructure in December 2025. Targets included more than 30 wind and photovoltaic farms, a combined heat and power (CHP) plant, and a manufacturing sector company. The attacks on the distributed energy resources (DER) disrupted communications between affected facilities and the distribution system operator, but did not impact electricity generation or heat supply. Across the campaign, threat actors deployed two previously undocumented wiper tools, [DynoWiper](https://attack.mitre.org/software/S9038), a Windows-based wiper and [LazyWiper](https://attack.mitre.org/software/S9039), a PowerShell wiper, distributed via malicious Group Policy Objects. At the CHP plant, threat actors had maintained access since at least March 2025, using that foothold to obtain credentials and move laterally before attempting wiper deployment. Some reporting has assessed the activity to be consistent with Russian Federal Security Service (FSB) threat activity group [Dragonfly](https://attack.mitre.org/groups/G0035), also tracked as STATIC TUNDRA, while other reporting attributes the destructive wiper activities to the Russian General Staff Main Intelligence Directorate (GRU) threat activity group ELECTRUM, also tracked as [Sandworm Team](https://attack.mitre.org/groups/G0034).(Citation: CERT Polska)(Citation: Dragos ELECTRUM JAN 2026)(Citation: ESET DynoWiper JAN 2026)(Citation: ESET DynoWiper Update JAN 2026)

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
