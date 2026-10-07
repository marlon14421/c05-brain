---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0019"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0019: Pod Creation — Defensive Application

## Source record

- [[01 ATT&CK/DC0019 - Pod Creation|DC0019 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The initial deployment or instantiation of a new pod in a containerized environment. This includes creating a pod manually, through orchestration tools (Kubernetes), or via Infrastructure-as-Code (IaC) configurations. A Pod is the smallest deployable unit in Kubernetes, typically containing one or more containers. Creation methods include: - Direct pod deployment (`kubectl run`, `kubectl apply`) - Automated deployment via CI/CD pipelines (e.g., ArgoCD, Jenkins, GitOps) - Infrastructure-as-Code (IaC) templates (e.g., Terraform, Helm Charts) - API-based deployments via Kubernetes control plane (create_pod API calls) - Pods can be ephemeral (short-lived) or persistent (part of a StatefulSet or Deployment). *Data Collection Measures:* - Kubernetes Audit Logs - Captures all API requests, including pod `create` events. - Kube-api server Logs - Monitors API calls related to pod deployments and modifications. Related Events: `PodSandboxChanged`, `SyncLoop`, `Created pod` - Container Runtime Logs - Logs from CRI-O, containerd, or Docker capture pod creation events. Related Events: `container start`, `container create` - Cloud Provider Logs - GKE, EKS, AKS logs provide insights into Kubernetes API interactions. - SIEM & Log Aggregation - Integrates Kubernetes logs into SIEM solutions. - EDR/XDR Solutions - Monitors container-based activity for anomalous pod creations.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
