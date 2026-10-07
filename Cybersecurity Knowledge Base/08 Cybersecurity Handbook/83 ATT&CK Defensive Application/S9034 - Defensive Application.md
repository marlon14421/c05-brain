---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9034"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9034: Tsundere Botnet — Defensive Application

## Source record

- [[01 ATT&CK/S9034 - Tsundere Botnet|S9034 source record]]
- ATT&CK class: Malware
- Platforms: Linux, macOS, Windows
- Tactics: Not specified

## Source context

[Tsundere Botnet](https://attack.mitre.org/software/S9034) is a botnet first reported in mid-2025 that is delivered via MSI installer or a PowerShell script. It leverages Node.js and JavaScript for payload delivery and execution, and uses smart contracts on the blockchain to host command and control (C2) addresses. [Tsundere Botnet](https://attack.mitre.org/software/S9034) is attributed to a likely Russian-speaking threat actor. A variant named DinDoor has been linked to [MuddyWater](https://attack.mitre.org/groups/G0069) operations and uses the Deno runtime for execution rather than Node.js.(Citation: Checkpoint_MOISCyberCrime_Mar2026)(Citation: SOCRadar_MuddyWaterDindoor_Mar2026)(Citation: CAL_MuddyWater_Mar2026)(Citation: SecureListUbiedo_Tsundere_Nov2025)

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
