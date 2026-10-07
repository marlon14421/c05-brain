---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0029"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0029: Cutting Edge — Defensive Application

## Source record

- [[01 ATT&CK/C0029 - Cutting Edge|C0029 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[Cutting Edge](https://attack.mitre.org/campaigns/C0029) was a campaign conducted by suspected China-nexus espionage actors, variously identified as UNC5221/UTA0178 and UNC5325, that began as early as December 2023 with the exploitation of zero-day vulnerabilities in Ivanti Connect Secure (previously Pulse Secure) VPN appliances. [Cutting Edge](https://attack.mitre.org/campaigns/C0029) targeted the U.S. defense industrial base and multiple sectors globally including telecommunications, financial, aerospace, and technology. [Cutting Edge](https://attack.mitre.org/campaigns/C0029) featured the use of defense evasion and living-off-the-land (LoTL) techniques along with the deployment of web shells and other custom malware.(Citation: Mandiant Cutting Edge January 2024)(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)(Citation: Volexity Ivanti Global Exploitation January 2024)(Citation: Mandiant Cutting Edge Part 2 January 2024)(Citation: Mandiant Cutting Edge Part 3 February 2024)

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
