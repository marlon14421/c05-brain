---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0076"
source_url: "https://attack.mitre.org/datacomponents/DC0076"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0076: Instance Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0076  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The initial provisioning and construction of a virtual machine (VM) or compute instance within a cloud infrastructure environment. This activity involves defining and allocating resources such as CPU, memory, storage, and networking to spin up a new compute instance. Examples: - AWS: creating an EC2 instance using RunInstances API calls. - Azure, creating a VM through the Azure Resource Manager (ARM). - GCP, an `instance.insert` action recorded.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0076](https://attack.mitre.org/datacomponents/DC0076)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
