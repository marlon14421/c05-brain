---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0077"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0077: Container Start — Defensive Application

## Source record

- [[01 ATT&CK/DC0077 - Container Start|DC0077 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

"Container Start" data component captures events related to the activation or invocation of a container within a containerized environment. This includes starting a previously stopped container, restarting an existing container, or initializing a container for runtime. Monitoring these activities is critical for identifying unauthorized or unexpected container activations, which may indicate potential adversarial activity or misconfigurations. Examples: - Docker Example: `docker start `, `docker restart ` - Kubernetes Example: Kubernetes automatically restarts containers as part of pod lifecycle management (e.g., due to health checks or configuration changes). - Cloud-Native Example - AWS ECS: API Call: StartTask to activate a stopped ECS task. - Azure Container Instances: Command to restart a container group instance. - GCP Kubernetes Engine: Automatic restarts as part of node or pod management. This data component can be collected through the following measures: - Docker Audit Logging: Enable Docker logging to capture start and restart events. Use tools like auditd to monitor terminal activity involving container lifecycle commands. - Kubernetes Audit Logs: Enable Kubernetes API server audit logging. - Cloud Provider Logs - AWS CloudTrail: Capture StartTask or related API calls for ECS. - Azure Monitor: Track activity in container groups that indicate start or restart events. - GCP Cloud Logging: Record logs related to pod restarts or scaling events in Kubernetes Engine. - SIEM Integration: Collect logs from Docker, Kubernetes, and cloud services to correlate container start events.

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
