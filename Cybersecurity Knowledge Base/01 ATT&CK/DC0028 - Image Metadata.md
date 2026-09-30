---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0028"
source_url: "https://attack.mitre.org/datacomponents/DC0028"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0028: Image Metadata

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0028  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

contextual information associated with a virtual machine image, such as its name, resource group, status (active or inactive), type (custom or prebuilt), size, creation date, and permissions. This metadata is critical for understanding the state and configuration of virtual machine images in cloud environments. Examples: - Azure Compute Service Image Metadata Example: - Name: MyCustomImage - Resource Group: MyResourceGroup - State: Available - Type: Managed Image - AWS EC2 AMI Metadata Example: - Image ID: ami-1234567890abcdef0 - Name: ProdImage - State: Available - Platform: Windows - Google Cloud Compute Engine Image Metadata Example: - Image Name: webserver-image - Project: my-project-id - Family: webserver - Source Disk: my-disk-id - VMware vSphere Template Metadata Example: - Name: LinuxTemplate - Disk Size: 40GB - Network Adapter: VM Network

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0028](https://attack.mitre.org/datacomponents/DC0028)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
