---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1057"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1057: Process Discovery — Defensive Application

## Source record

- [[01 ATT&CK/T1057 - Process Discovery|T1057 source record]]
- ATT&CK class: Technique
- Platforms: ESXi, Linux, macOS, Network Devices, Windows
- Tactics: discovery

## Source context

Adversaries may attempt to get information about running processes on a system. Information obtained could be used to gain an understanding of common software/applications running on systems within the network. Administrator or otherwise elevated access may provide better process details. Adversaries may use the information from [Process Discovery](https://attack.mitre.org/techniques/T1057) during automated discovery to shape follow-on behaviors, including whether or not the adversary fully infects the target and/or attempts specific actions. In Windows environments, adversaries could obtain details on running processes using the [Tasklist](https://attack.mitre.org/software/S0057) utility via [cmd](https://attack.mitre.org/software/S0106) or Get-Process via [PowerShell](https://attack.mitre.org/techniques/T1059/001). Information about processes can also be extracted from the output of [Native API](https://attack.mitre.org/techniques/T1106) calls such as CreateToolhelp32Snapshot . In Mac and Linux, this is accomplished with the ps command. Adversaries may also opt to enumerate processes via `/proc`. ESXi also supports use of the `ps` command, as well as `esxcli system process list`.(Citation: Sygnia ESXi Ransomware 2025)(Citation: Crowdstrike Hypervisor Jackpotting Pt 2 2021) On network devices, [Network Device CLI](https://attack.mitre.org/techniques/T1059/008) commands such as `show processes` can be used to display current running processes.(Citation: US-CERT-TA18-106A)(Citation: show_processes_cisco_cmd)

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
