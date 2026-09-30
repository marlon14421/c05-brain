---
type: "Malware"
source: MITRE ATT&CK
id: "S1237"
source_url: "https://attack.mitre.org/software/S1237"
created: "2025-09-12"
modified: "2025-10-22"
---
# S1237: CANONSTAGER

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1237  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[CANONSTAGER](https://attack.mitre.org/software/S1237) is a loader known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2025. [Mustang Panda](https://attack.mitre.org/groups/G0129) utilizes DLL side-loading to execute within the victim environment prior to delivering a follow-on malicious encrypted payload. [CANONSTAGER](https://attack.mitre.org/software/S1237) leverages Thread Local Storage (TLS) and Native Windows APIs within the victim environment to elude detections. [CANONSTAGER](https://attack.mitre.org/software/S1237) also hides its code utilizing window procedures and message queues.(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1237](https://attack.mitre.org/software/S1237)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
