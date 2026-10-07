---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1652"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1652: Device Driver Discovery — Defensive Application

## Source record

- [[01 ATT&CK/T1652 - Device Driver Discovery|T1652 source record]]
- ATT&CK class: Technique
- Platforms: Linux, macOS, Windows
- Tactics: discovery

## Source context

Adversaries may attempt to enumerate local device drivers on a victim host. Information about device drivers may highlight various insights that shape follow-on behaviors, such as the function/purpose of the host, present security tools (i.e. [Security Software Discovery](https://attack.mitre.org/techniques/T1518/001)) or other defenses (e.g., [Virtualization/Sandbox Evasion](https://attack.mitre.org/techniques/T1497)), as well as potential exploitable vulnerabilities (e.g., [Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)). Many OS utilities may provide information about local device drivers, such as `driverquery.exe` and the `EnumDeviceDrivers()` API function on Windows.(Citation: Microsoft Driverquery)(Citation: Microsoft EnumDeviceDrivers) Information about device drivers (as well as associated services, i.e., [System Service Discovery](https://attack.mitre.org/techniques/T1007)) may also be available in the Registry.(Citation: Microsoft Registry Drivers) On Linux/macOS, device drivers (in the form of kernel modules) may be visible within `/dev` or using utilities such as `lsmod` and `modinfo`.(Citation: Linux Kernel Programming)(Citation: lsmod man)(Citation: modinfo man)

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
