---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0059"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0059: Salesforce Data Exfiltration — Defensive Application

## Source record

- [[01 ATT&CK/C0059 - Salesforce Data Exfiltration|C0059 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

The [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059) campaign began in October 2024 with financially-motivated threat actor UNC6040 using [Spearphishing Voice](https://attack.mitre.org/techniques/T1598/004) (vishing) to compromise corporate Salesforce instances for large-scale data theft and extortion. Following the initial data theft, victim organizations received extortion demands from a separate threat actor, UNC6240, who claimed to be the “ShinyHunters” group. The observed infrastructure and TTPs used during the [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059) campaign overlap with those used by threat groups with suspected ties to the broader collective known as "The Com.” These overlaps could plausibly be the result of associated actors operating within the same communities and are not necessarily an indication of a direct operational relationship.(Citation: FBI Salesforce Data Theft SEP 2025)(Citation: Google Salesforce JUN 2025)

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
