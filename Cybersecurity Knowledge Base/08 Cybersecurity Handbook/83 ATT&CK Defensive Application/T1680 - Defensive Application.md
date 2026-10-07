---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1680"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1680: Local Storage Discovery — Defensive Application

## Source record

- [[01 ATT&CK/T1680 - Local Storage Discovery|T1680 source record]]
- ATT&CK class: Technique
- Platforms: ESXi, IaaS, Linux, macOS, Windows
- Tactics: discovery

## Source context

Adversaries may enumerate local drives, disks, and/or volumes and their attributes like total or free space and volume serial number. This can be done to prepare for ransomware-related encryption, to perform [Lateral Movement](https://attack.mitre.org/tactics/TA0109), or as a precursor to [Direct Volume Access](https://attack.mitre.org/techniques/T1006). On ESXi systems, adversaries may use [Hypervisor CLI](https://attack.mitre.org/techniques/T1059/012) commands such as `esxcli` to list storage connected to the host as well as `.vmdk` files.(Citation: TrendMicro)(Citation: TrendMicro ESXI Ransomware) On Windows systems, adversaries can use `wmic logicaldisk get` to find information about local network drives. They can also use `Get-PSDrive` in PowerShell to retrieve drives and may additionally use Windows API functions such as `GetDriveType`.(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)(Citation: Volexity) Linux has commands such as `parted`, `lsblk`, `fdisk`, `lshw`, and `df` that can list information about disk partitions such as size, type, file system types, and free space. The command `diskutil` on MacOS can be used to list disks while `system_profiler SPStorageDataType` can additionally show information such as a volume’s mount path, file system, and the type of drive in the system. Infrastructure as a Service (IaaS) cloud providers also have commands for storage discovery such as `describe volume` in AWS, `gcloud compute disks list` in GCP, and `az disk list` in Azure.(Citation: AWS docs describe volumes)(Citation: GCP gcloud compute disks list)(Citation: azure az disk)

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
