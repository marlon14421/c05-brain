---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0105"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0105: Group Metadata — Defensive Application

## Source record

- [[01 ATT&CK/DC0105 - Group Metadata|DC0105 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Group metadata includes attributes like name, permissions, purpose, and associated user accounts or roles, which adversaries may exploit for privilege escalation. Examples: - Active Directory: `Get-ADGroup -Identity "Domain Admins" -Properties Members, Description` - Azure AD: `Get-AzureADGroup -ObjectId ` - Google Workspace: `GET https://admin.googleapis.com/admin/directory/v1/groups/ ` - AWS IAM: `aws iam list-group-policies --group-name ` - Office 365: `GET https://graph.microsoft.com/v1.0/groups/ ` *Data Collection Measures:* - Cloud Logging: - AWS CloudTrail for IAM group-related activities. - Azure AD Sign-In/Audit logs for metadata changes. - Google Admin Activity logs for API calls. - Directory Logging: Log metadata access (e.g., Windows Event ID 4662). - API Monitoring: Log API calls to modify group metadata (e.g., Microsoft Graph API). - SIEM Integration: Centralize group metadata logs for analysis.

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
