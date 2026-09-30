---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0080"
source_url: "https://attack.mitre.org/datacomponents/DC0080"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0080: Instance Start

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0080  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The initiation or activation of a virtual machine instance within a cloud infrastructure. This action typically involves starting an existing instance that had been stopped or paused, allowing it to resume operation. Examples: - Google Cloud Platform (GCP): Starting an instance through `instance.start` API activity. - AWS: Logging of `StartInstances` in AWS CloudTrail for EC2 instances. - Azure: `Microsoft.Compute/virtualMachines/start` entries indicate a VM instance being started.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0080](https://attack.mitre.org/datacomponents/DC0080)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
