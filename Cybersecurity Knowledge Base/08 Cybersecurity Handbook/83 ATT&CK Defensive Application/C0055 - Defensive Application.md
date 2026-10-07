---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0055"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0055: Quad7 Activity — Defensive Application

## Source record

- [[01 ATT&CK/C0055 - Quad7 Activity|C0055 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

Quad7 Activity, also known as CovertNetwork-1658 or the 7777 Botnet, is a network of compromised small office/home office (SOHO) routers. (Citation: Bitsight 7777 Botnet) (Citation: Microsoft Storm-0940) The botnet was initially composed primarily of TP-Link routers and was named Quad7 due to compromised devices exposing TCP port 7777 with the distinctive banner xlogin . Later activity showed a significant increase in compromised Asus routers and the addition of new ports and banners, including TCP port 63256 displaying alogin . Quad7 infrastructure functions as a collection of egress IPs that various China-affiliated threat actors have used to conduct password-spraying and brute-force operations. (Citation: Bitsight 7777 Botnet)(Citation: Medium 777-Botnet) Microsoft has reported that Storm-0940 leveraged credentials obtained through Quad7 Activity to target organizations in North America and Europe, including government agencies, non-governmental organizations, think tanks, law firms, energy firms, IT providers, and defense industrial base entities. (Citation: Microsoft Storm-0940)

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
