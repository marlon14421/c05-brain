---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S1035"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S1035: Small Sieve — Defensive Application

## Source record

- [[01 ATT&CK/S1035 - Small Sieve|S1035 source record]]
- ATT&CK class: Malware
- Platforms: Windows
- Tactics: Not specified

## Source context

[Small Sieve](https://attack.mitre.org/software/S1035) is a Telegram Bot API-based Python backdoor that has been distributed using a Nullsoft Scriptable Install System (NSIS) Installer; it has been used by [MuddyWater](https://attack.mitre.org/groups/G0069) since at least January 2022.(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: NCSC GCHQ Small Sieve Jan 2022) Security researchers have also noted [Small Sieve](https://attack.mitre.org/software/S1035)'s use by UNC3313, which may be associated with [MuddyWater](https://attack.mitre.org/groups/G0069).(Citation: Mandiant UNC3313 Feb 2022)

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
