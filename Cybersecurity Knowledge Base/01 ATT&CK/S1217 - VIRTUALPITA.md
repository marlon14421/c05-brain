---
type: "Malware"
source: MITRE ATT&CK
id: "S1217"
source_url: "https://attack.mitre.org/software/S1217"
created: "2025-06-02"
modified: "2025-06-03"
---
# S1217: VIRTUALPITA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1217  
**Platforms:** ESXi, Linux  
**Tactics:** Not specified

## Source description

[VIRTUALPITA](https://attack.mitre.org/software/S1217) is a passive backdoor with ESXi and Linux vCenter variants capable of command execution, file transfer, and starting and stopping processes. [VIRTUALPITA](https://attack.mitre.org/software/S1217) has been in use since at least 2022 including by [UNC3886](https://attack.mitre.org/groups/G1048) who leveraged malicious vSphere Installation Bundles (VIBs) for install on ESXi hypervisors.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1217](https://attack.mitre.org/software/S1217)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
