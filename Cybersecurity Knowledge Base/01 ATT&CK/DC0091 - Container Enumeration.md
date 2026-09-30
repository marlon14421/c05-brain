---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0091"
source_url: "https://attack.mitre.org/datacomponents/DC0091"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0091: Container Enumeration

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0091  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

"Container Enumeration" data component captures events and actions related to listing and identifying active or available containers within a containerized environment. This includes information about running, stopped, or configured containers, such as their names, IDs, statuses, or associated images. Monitoring this activity is crucial for detecting unauthorized discovery or reconnaissance efforts. Examples: - Docker Example: `docker ps`, `docker ps -a` - Kubernetes Example: `kubectl get pods`, `kubectl get deployments` - Cloud Container Services Example - AWS ECS: API Call: ListTasks or ListContainers - Azure Kubernetes Service: API Call: List pod or container instances. - Google Kubernetes Engine (GKE): API Call: Retrieve deployments and their associated containers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0091](https://attack.mitre.org/datacomponents/DC0091)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
