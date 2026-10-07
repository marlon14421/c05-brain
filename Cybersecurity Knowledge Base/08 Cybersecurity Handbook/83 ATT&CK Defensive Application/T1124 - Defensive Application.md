---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1124"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1124: System Time Discovery — Defensive Application

## Source record

- [[01 ATT&CK/T1124 - System Time Discovery|T1124 source record]]
- ATT&CK class: Technique
- Platforms: ESXi, Linux, macOS, Network Devices, Windows
- Tactics: discovery

## Source context

An adversary may gather the system time and/or time zone settings from a local or remote system. The system time is set and stored by services, such as the Windows Time Service on Windows or systemsetup on macOS.(Citation: MSDN System Time)(Citation: Technet Windows Time Service)(Citation: systemsetup mac time) These time settings may also be synchronized between systems and services in an enterprise network, typically accomplished with a network time server within a domain.(Citation: Mac Time Sync)(Citation: linux system time) System time information may be gathered in a number of ways, such as with [Net](https://attack.mitre.org/software/S0039) on Windows by performing net time \\hostname to gather the system time on a remote system. The victim's time zone may also be inferred from the current system time or gathered by using w32tm /tz .(Citation: Technet Windows Time Service) In addition, adversaries can discover device uptime through functions such as GetTickCount() to determine how long it has been since the system booted up.(Citation: Virtualization/Sandbox Evasion) On network devices, [Network Device CLI](https://attack.mitre.org/techniques/T1059/008) commands such as `show clock detail` can be used to see the current time configuration.(Citation: show_clock_detail_cisco_cmd) On ESXi servers, `esxcli system clock get` can be used for the same purpose. In addition, system calls – such as time() – have been used to collect the current time on Linux devices.(Citation: MAGNET GOBLIN) On macOS systems, adversaries may use commands such as systemsetup -gettimezone or timeIntervalSinceNow to gather current time zone information or current date and time.(Citation: System Information Discovery Technique)(Citation: ESET DazzleSpy Jan 2022) This information could be useful for performing other techniques, such as executing a file with a [Scheduled Task/Job](https://attack.mitre.org/techniques/T1053)(Citation: RSA EU12 They're Inside), or to discover locality information based on time zone to assist in victim targeting (i.e. [System Location Discovery](https://attack.mitre.org/techniques/T1614)). Adversaries may also use knowledge of system time as part of a time bomb, or delaying execution until a specified date/time.(Citation: AnyRun TimeBomb)

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
