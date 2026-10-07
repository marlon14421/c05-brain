---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0035"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0035: KV Botnet Activity — Defensive Application

## Source record

- [[01 ATT&CK/C0035 - KV Botnet Activity|C0035 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) consisted of exploitation of primarily “end-of-life” small office-home office (SOHO) equipment from manufacturers such as Cisco, NETGEAR, and DrayTek. [KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) was used by [Volt Typhoon](https://attack.mitre.org/groups/G1017) to obfuscate connectivity to victims in multiple critical infrastructure segments, including energy and telecommunication companies and entities based on the US territory of Guam. While the KV Botnet is the most prominent element of this campaign, it overlaps with another botnet cluster referred to as the JDY cluster.(Citation: Lumen KVBotnet 2023) This botnet was disrupted by US law enforcement entities in early 2024 after periods of activity from October 2022 through January 2024.(Citation: DOJ KVBotnet 2024)

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
