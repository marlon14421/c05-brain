---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "G1044"
attack_type: "Threat Group"
source: MITRE ATT&CK
---
# G1044: APT42 — Defensive Application

## Source record

- [[01 ATT&CK/G1044 - APT42|G1044 source record]]
- ATT&CK class: Threat Group
- Platforms: Not specified
- Tactics: Not specified

## Source context

[APT42](https://attack.mitre.org/groups/G1044) is an Iranian-sponsored threat group that conducts cyber espionage and surveillance.(Citation: Mandiant APT42-charms) The group primarily focuses on targets in the Middle East region, but has targeted a variety of industries and countries since at least 2015.(Citation: Mandiant APT42-charms) [APT42](https://attack.mitre.org/groups/G1044) starts cyber operations through spearphishing emails and/or the PINEFLOWER Android malware, then monitors and collects information from the compromised systems and devices.(Citation: Mandiant APT42-charms) Finally, [APT42](https://attack.mitre.org/groups/G1044) exfiltrates data using native features and open-source tools.(Citation: Mandiant APT42-untangling) [APT42](https://attack.mitre.org/groups/G1044) activities have been linked to [Magic Hound](https://attack.mitre.org/groups/G0059) by other commercial vendors. While there are behavior and software overlaps between [Magic Hound](https://attack.mitre.org/groups/G0059) and [APT42](https://attack.mitre.org/groups/G1044), they appear to be distinct entities and are tracked as separate entities by their originating vendor.

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
