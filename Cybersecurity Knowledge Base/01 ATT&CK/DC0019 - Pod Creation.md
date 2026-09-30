---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0019"
source_url: "https://attack.mitre.org/datacomponents/DC0019"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0019: Pod Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0019  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The initial deployment or instantiation of a new pod in a containerized environment. This includes creating a pod manually, through orchestration tools (Kubernetes), or via Infrastructure-as-Code (IaC) configurations. A Pod is the smallest deployable unit in Kubernetes, typically containing one or more containers. Creation methods include: - Direct pod deployment (`kubectl run`, `kubectl apply`) - Automated deployment via CI/CD pipelines (e.g., ArgoCD, Jenkins, GitOps) - Infrastructure-as-Code (IaC) templates (e.g., Terraform, Helm Charts) - API-based deployments via Kubernetes control plane (create_pod API calls) - Pods can be ephemeral (short-lived) or persistent (part of a StatefulSet or Deployment). *Data Collection Measures:* - Kubernetes Audit Logs - Captures all API requests, including pod `create` events. - Kube-api server Logs - Monitors API calls related to pod deployments and modifications. Related Events: `PodSandboxChanged`, `SyncLoop`, `Created pod` - Container Runtime Logs - Logs from CRI-O, containerd, or Docker capture pod creation events. Related Events: `container start`, `container create` - Cloud Provider Logs - GKE, EKS, AKS logs provide insights into Kubernetes API interactions. - SIEM & Log Aggregation - Integrates Kubernetes logs into SIEM solutions. - EDR/XDR Solutions - Monitors container-based activity for anomalous pod creations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0019](https://attack.mitre.org/datacomponents/DC0019)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
