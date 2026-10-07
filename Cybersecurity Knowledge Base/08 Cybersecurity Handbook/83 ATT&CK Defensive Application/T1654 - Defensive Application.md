---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1654"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1654: Log Enumeration — Defensive Application

## Source record

- [[01 ATT&CK/T1654 - Log Enumeration|T1654 source record]]
- ATT&CK class: Technique
- Platforms: ESXi, IaaS, Linux, macOS, Windows
- Tactics: discovery

## Source context

Adversaries may enumerate system and service logs to find useful data. These logs may highlight various types of valuable insights for an adversary, such as user authentication records ([Account Discovery](https://attack.mitre.org/techniques/T1087)), security or vulnerable software ([Software Discovery](https://attack.mitre.org/techniques/T1518)), or hosts within a compromised network ([Remote System Discovery](https://attack.mitre.org/techniques/T1018)). Host binaries may be leveraged to collect system logs. Examples include using `wevtutil.exe` or [PowerShell](https://attack.mitre.org/techniques/T1059/001) on Windows to access and/or export security event information.(Citation: WithSecure Lazarus-NoPineapple Threat Intel Report 2023)(Citation: Cadet Blizzard emerges as novel threat actor) In cloud environments, adversaries may leverage utilities such as the Azure VM Agent’s `CollectGuestLogs.exe` to collect security logs from cloud hosted infrastructure.(Citation: SIM Swapping and Abuse of the Microsoft Azure Serial Console) Adversaries may also target centralized logging infrastructure such as SIEMs. Logs may also be bulk exported and sent to adversary-controlled infrastructure for offline analysis. In addition to gaining a better understanding of the environment, adversaries may also monitor logs in real time to track incident response procedures. This may allow them to adjust their techniques in order to maintain persistence or evade defenses.(Citation: Permiso GUI-Vil 2023)

## Defensive focus

Map the recorded behavior or objective to assets, trust boundaries, identities, and defensive controls in the local environment. ATT&CK classification alone does not establish activity or compromise.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets, roles, platforms, and business services are actually exposed to this behavior?
- What prevention or hardening control applies, and which owner maintains it?
- Which telemetry source can support or refute the behavior, and what blind spots remain?
- What legitimate administrative or software behavior could look similar?
- What containment or recovery decision is authorized if evidence is confirmed?

## Safe validation

Use an isolated lab, benign simulation, or sanitized historical data. Test only owned or explicitly authorized systems; do not reproduce harmful behavior against production targets. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
