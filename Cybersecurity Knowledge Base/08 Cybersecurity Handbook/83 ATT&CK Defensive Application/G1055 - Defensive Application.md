---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1055"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1055: VOID MANTICORE — Defensive Application

## Source record

- [[01 ATT&CK/G1055 - VOID MANTICORE|G1055 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) is a threat group assessed to operate on behalf of Iran’s Ministry of Intelligence and Security (MOIS).(Citation: Check Point VOID MANTICORE Handala Hack March 2026) Active since at least mid-2022, VOID MANTICORE has targeted government entities, critical infrastructure, and private sector organizations across Albania, Israel, and the United States.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)(Citation: Palo Alto VOID MANTICORE Iran Cyber Threats March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) conducts destructive cyber operations, combining wiper attacks with hack-and-leak campaigns. The group has operated under multiple public-facing personas, including [HomeLand Justice](https://attack.mitre.org/campaigns/C0038) in operations against Albania, Karma and Karma Below in campaigns targeting Israeli organizations, and Handala Hack, its current primary persona, which has claimed activity against Israeli and U.S. entities, including a March 2026 attack against Stryker Corporation.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)(Citation: DOJ FBI Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has been observed collaborating with Scarred Manticore, which has been linked to initial access operations preceding VOID MANTICORE’s activity.(Citation: Domain Tools Handala Hack Karma Homeland Justice MOIS April 2026)

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
