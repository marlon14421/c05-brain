---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G0069"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G0069: MuddyWater — Defensive Application

## Source record

- [[01 ATT&CK/G0069 - MuddyWater|G0069 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[MuddyWater](https://attack.mitre.org/groups/G0069) is a cyber espionage group assessed to be a subordinate element within Iran's Ministry of Intelligence and Security (MOIS).(Citation: CYBERCOM Iranian Intel Cyber January 2022) Since at least 2017, [MuddyWater](https://attack.mitre.org/groups/G0069) has targeted a range of government and private organizations across sectors, including telecommunications, local government, finance, defense, and oil and natural gas organizations, in the Middle East (specifically the UAE and Saudi Arabia), Asia, Africa, Europe, and North America. [MuddyWater](https://attack.mitre.org/groups/G0069) has reused domains dating back to October 2025, and has a preference for NameCheap and Hosterdaddy Private Limited (AS136557). In late 2025 and early 2026, [MuddyWater](https://attack.mitre.org/groups/G0069) used commercial satellite internet (i.e., Starlink) for command and control (C2) communication. (Citation: FalconFeeds_Iran_Mar2026)(Citation: Huntio_IranInfra_Mar2026)(Citation: Unit 42 MuddyWater Nov 2017)(Citation: Symantec MuddyWater Dec 2018)(Citation: ClearSky MuddyWater Nov 2018)(Citation: ClearSky MuddyWater June 2019)(Citation: Reaqta MuddyWater November 2017)(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: Talos MuddyWater Jan 2022)(Citation: NaumaanProofpoint_GlobalClickFix_April2025)(Citation: ESET_MuddyWater_Dec2025)(Citation: SymantecCarbonBlack_Seedworm_Mar2026)

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
