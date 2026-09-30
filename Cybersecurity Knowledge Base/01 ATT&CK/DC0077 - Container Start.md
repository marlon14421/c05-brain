---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0077"
source_url: "https://attack.mitre.org/datacomponents/DC0077"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0077: Container Start

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0077  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

"Container Start" data component captures events related to the activation or invocation of a container within a containerized environment. This includes starting a previously stopped container, restarting an existing container, or initializing a container for runtime. Monitoring these activities is critical for identifying unauthorized or unexpected container activations, which may indicate potential adversarial activity or misconfigurations. Examples: - Docker Example: `docker start `, `docker restart ` - Kubernetes Example: Kubernetes automatically restarts containers as part of pod lifecycle management (e.g., due to health checks or configuration changes). - Cloud-Native Example - AWS ECS: API Call: StartTask to activate a stopped ECS task. - Azure Container Instances: Command to restart a container group instance. - GCP Kubernetes Engine: Automatic restarts as part of node or pod management. This data component can be collected through the following measures: - Docker Audit Logging: Enable Docker logging to capture start and restart events. Use tools like auditd to monitor terminal activity involving container lifecycle commands. - Kubernetes Audit Logs: Enable Kubernetes API server audit logging. - Cloud Provider Logs - AWS CloudTrail: Capture StartTask or related API calls for ECS. - Azure Monitor: Track activity in container groups that indicate start or restart events. - GCP Cloud Logging: Record logs related to pod restarts or scaling events in Kubernetes Engine. - SIEM Integration: Collect logs from Docker, Kubernetes, and cloud services to correlate container start events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0077](https://attack.mitre.org/datacomponents/DC0077)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
