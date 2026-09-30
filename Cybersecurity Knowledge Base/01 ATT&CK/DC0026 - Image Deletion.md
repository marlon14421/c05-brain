---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0026"
source_url: "https://attack.mitre.org/datacomponents/DC0026"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0026: Image Deletion

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0026  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Removal of a virtual machine image in a cloud infrastructure (ex: Azure Compute Service Images DELETE) Examples: - Azure Compute Service Image Deletion - Example: Deleting a virtual machine image using Azure CLI: `az image delete --name MyImage --resource-group MyResourceGroup` - AWS EC2 AMI (Amazon Machine Image) Deletion - Example: Deregistering an AMI in AWS: `aws ec2 deregister-image --image-id ami-1234567890abcdef0` - Google Cloud Compute Engine Image Deletion - Example: Deleting a custom image in Google Cloud: `gcloud compute images delete my-custom-image` - VMware vSphere - Example: Deleting a VM image/template from a vSphere environment: This data component can be collected through the following measures: Enable Cloud Platform Logging - Azure: Enable "Activity Logs" to capture DELETE requests to `Microsoft.Compute/images`. - AWS: Use AWS CloudTrail to monitor `DeregisterImage` or `DeleteSnapshot` API calls. - Google Cloud: Enable "Cloud Audit Logs" to track image deletion events under `compute.googleapis.com/images`. API Monitoring - Monitor API activity to track the deletion of images using: - AWS SDK/CLI `DeregisterImage` or `DeleteSnapshot`. - Azure REST API DELETE operations for images. - Google Cloud Compute Engine APIs for image deletion. Cloud SIEM Integration - Ingest logs into a centralized SIEM platform for monitoring and alerting: Event Correlation - Correlate image deletion events with unusual account activity or concurrent unauthorized operations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0026](https://attack.mitre.org/datacomponents/DC0026)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
