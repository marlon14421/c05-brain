---
type: "Malware"
source: MITRE ATT&CK
id: "S1218"
source_url: "https://attack.mitre.org/software/S1218"
created: "2025-06-04"
modified: "2025-06-04"
---
# S1218: VIRTUALPIE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1218  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

[VIRTUALPIE](https://attack.mitre.org/software/S1218) is a lightweight backdoor written in Python that spawns an IPv6 listener on a VMware ESXi server and features command line execution, file transfer, and reverse shell capabilities. [VIRTUALPIE](https://attack.mitre.org/software/S1218) has been in use since at least 2022 including by [UNC3886](https://attack.mitre.org/groups/G1048) who installed it via malicious vSphere Installation Bundles (VIBs).(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1218](https://attack.mitre.org/software/S1218)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
