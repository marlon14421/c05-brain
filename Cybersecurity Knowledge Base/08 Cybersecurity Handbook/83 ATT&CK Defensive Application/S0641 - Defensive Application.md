---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S0641"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S0641: Kobalos — Defensive Application

## Source record

- [[01 ATT&CK/S0641 - Kobalos|S0641 source record]]
- ATT&CK class: Malware
- Platforms: Linux
- Tactics: Not specified

## Source context

[Kobalos](https://attack.mitre.org/software/S0641) is a multi-platform backdoor that can be used against Linux, FreeBSD, and Solaris. [Kobalos](https://attack.mitre.org/software/S0641) has been deployed against high profile targets, including high-performance computers, academic servers, an endpoint security vendor, and a large internet service provider; it has been found in Europe, North America, and Asia. [Kobalos](https://attack.mitre.org/software/S0641) was first identified in late 2019.(Citation: ESET Kobalos Feb 2021)(Citation: ESET Kobalos Jan 2021)

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
