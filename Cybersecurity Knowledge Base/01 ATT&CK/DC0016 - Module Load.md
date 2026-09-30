---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0016"
source_url: "https://attack.mitre.org/datacomponents/DC0016"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0016: Module Load

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0016  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

When a process or program dynamically attaches a shared library, module, or plugin into its memory space. This action is typically performed to extend the functionality of an application, access shared system resources, or interact with kernel-mode components.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0016](https://attack.mitre.org/datacomponents/DC0016)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
