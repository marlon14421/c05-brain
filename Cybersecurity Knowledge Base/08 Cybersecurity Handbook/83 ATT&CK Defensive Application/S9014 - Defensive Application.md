---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9014"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9014: PHASEJAM — Defensive Application

## Source record

- [[01 ATT&CK/S9014 - PHASEJAM|S9014 source record]]
- ATT&CK class: Malware
- Platforms: Linux, Network Devices
- Tactics: Not specified

## Source context

[PHASEJAM](https://attack.mitre.org/software/S9014) is a dropper written as a bash shell script that modifies Ivanti Connect Secure appliance components. [PHASEJAM](https://attack.mitre.org/software/S9014) was first reported in January 2025. [PHASEJAM](https://attack.mitre.org/software/S9014) has previously been leveraged by People's Republic of China (PRC)- affiliated actors identified as UNC5221 and SYLVANITE.(Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: Google UNC5221 Ivanti January 2025)

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
