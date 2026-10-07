---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0022"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0022: Operation Dream Job — Defensive Application

## Source record

- [[01 ATT&CK/C0022 - Operation Dream Job|C0022 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[Operation Dream Job](https://attack.mitre.org/campaigns/C0022) was a cyber espionage operation likely conducted by [Lazarus Group](https://attack.mitre.org/groups/G0032) that targeted the defense, aerospace, government, and other sectors in the United States, Israel, Australia, Russia, and India. In at least one case, the cyber actors tried to monetize their network access to conduct a business email compromise (BEC) operation. In 2020, security researchers noted overlapping TTPs, to include fake job lures and code similarities, between [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), Operation North Star, and Operation Interception; by 2022 security researchers described [Operation Dream Job](https://attack.mitre.org/campaigns/C0022) as an umbrella term covering both Operation Interception and Operation North Star.(Citation: ClearSky Lazarus Aug 2020)(Citation: McAfee Lazarus Jul 2020)(Citation: ESET Lazarus Jun 2020)(Citation: The Hacker News Lazarus Aug 2022)

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
