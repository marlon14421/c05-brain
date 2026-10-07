---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0099"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0099: Group Enumeration — Defensive Application

## Source record

- [[01 ATT&CK/DC0099 - Group Enumeration|DC0099 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Extracting group lists from identity systems identifies permissions, roles, or configurations. Adversaries may exploit high-privilege groups or misconfigurations. Examples: - AWS CLI: `aws iam list-groups` - PowerShell: `Get-ADGroup -Filter *` - (Saas) Google Workspace: Admin SDK Directory API - Azure: `Get-AzureADGroup` - Microsoft 365: Graph API `GET https://graph.microsoft.com/v1.0/groups` *Data Collection Measures:* - Cloud Logging: Enable AWS CloudTrail, Azure Activity Logs, and Google Workspace Admin Logs for group-related actions. - Directory Monitoring: Track logs like AD Event ID 4662 (object operations). - API Monitoring: Log API activity like AWS IAM queries. - SaaS Monitoring: Use platform logs (e.g., Office 365 Unified Audit Logs). - SIEM Integration: Centralize group query tracking.

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
