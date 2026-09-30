---
type: "Malware"
source: MITRE ATT&CK
id: "S1238"
source_url: "https://attack.mitre.org/software/S1238"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1238: STATICPLUGIN

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1238  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[STATICPLUGIN](https://attack.mitre.org/software/S1238) is a downloader known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2025. [STATICPLUGIN](https://attack.mitre.org/software/S1238) has utilized a valid certificate in order to bypass endpoint security protections. [STATICPLUGIN](https://attack.mitre.org/software/S1238) masqueraded as legitimate software installer by using a custom TForm. [STATICPLUGIN](https://attack.mitre.org/software/S1238) has been leveraged to deploy a loader that facilitates follow on malware.(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1238](https://attack.mitre.org/software/S1238)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
