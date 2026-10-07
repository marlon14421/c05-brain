---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0074"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0074: Driver Metadata — Defensive Application

## Source record

- [[01 ATT&CK/DC0074 - Driver Metadata|DC0074 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

to contextual data about a driver, including its attributes, functionality, and activity. This can involve details such as the driver's origin, integrity, cryptographic signature, issues reported during its use, and runtime behavior. Examples include metadata captured during driver integrity checks, hash validation, or error reporting. Examples: - Driver Signature Validation: A driver is validated to ensure it is signed by a trusted Certificate Authority (CA). - Driver Hash Verification: The hash of a driver is compared to a known good hash stored in a database. - Driver Compatibility Issues: A driver error is logged due to compatibility issues with a particular version of the operating system. - Vulnerable Driver Identification: Metadata indicates the driver version is outdated or contains a known vulnerability. - Monitoring Driver Integrity: Drivers are monitored for any unauthorized modifications to their binary or associated files. This data component can be collected through the following measures: Windows - Windows Event Logs: - Event ID 3000-3006: Logs metadata about driver signature validation. - Event ID 2000-2011 (Windows Defender Application Control): Tracks driver integrity and policy enforcement. - Sysmon Logs: Configure Sysmon to capture driver loading metadata (Event ID 6). - Driver Verifier: Use Driver Verifier to collect diagnostic and performance data about drivers, including stability and compatibility metrics. - PowerShell: Use commands to retrieve metadata about installed drivers: `Get-WindowsDriver -Online | Select-Object Driver, ProviderName, Version` Linux - Auditd: Configure audit rules to monitor driver interactions and collect metadata: `auditctl -w /lib/modules/ -p rwxa -k driver_metadata` - dmesg: Use `dmesg` to extract kernel logs with driver metadata: `dmesg | grep "module"` - lsmod and modinfo: Commands to list loaded modules and retrieve metadata about drivers: `lsmod` | `modinfo ` macOS - Unified Logs: Collect metadata from system logs about kernel extensions (kexts): `log show --predicate 'eventMessage contains "kext load"' --info` - kextstat: Command to retrieve information about loaded kernel extensions: `kextstat` SIEM Tools - Ingest Driver Metadata: Collect driver metadata logs from Sysmon, Auditd, or macOS logs into SIEMs like Splunk or Elastic. Vulnerability Management Tools - Use these tools to collect metadata about vulnerable drivers across enterprise systems.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
