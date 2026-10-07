---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0030"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0030: Triton Safety Instrumented System Attack — Defensive Application

## Source record

- [[01 ATT&CK/C0030 - Triton Safety Instrumented System Attack|C0030 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

[Triton Safety Instrumented System Attack](https://attack.mitre.org/campaigns/C0030) was a campaign employed by [TEMP.Veles](https://attack.mitre.org/groups/G0088) which leveraged the [Triton](https://attack.mitre.org/software/S1009) malware framework against a petrochemical organization.(Citation: Triton-EENews-2017) The malware and techniques used within this campaign targeted specific Triconex [Safety Controller](https://attack.mitre.org/assets/A0010)s within the environment.(Citation: FireEye TRITON 2018) The incident was eventually discovered due to a safety trip that occurred as a result of an issue in the malware.(Citation: FireEye TRITON 2017)

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
