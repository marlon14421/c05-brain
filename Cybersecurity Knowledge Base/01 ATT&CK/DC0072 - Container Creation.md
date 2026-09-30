---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0072"
source_url: "https://attack.mitre.org/datacomponents/DC0072"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0072: Container Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0072  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

"Container Creation" data component captures details about the initial construction of a container in a containerized environment. This includes events where a new container is instantiated, such as through Docker, Kubernetes, or other container orchestration platforms. Monitoring these events helps detect unauthorized or potentially malicious container creation. Examples: - Docker Example: `docker create my-container`, `docker run --name=my-container nginx:latest` - Kubernetes Example: `kubectl run my-pod --image=nginx`, `kubectl create deployment my-deployment --image=nginx` - Cloud Container Services Example - AWS ECS: Task or service creation (`RunTask` or `CreateService`). - Azure Container Instances: Deployment of a container group. - Google Kubernetes Engine (GKE): Creation of new pods via GCP APIs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0072](https://attack.mitre.org/datacomponents/DC0072)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
