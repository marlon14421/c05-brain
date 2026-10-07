---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0094"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0094: Group Modification — Defensive Application

## Source record

- [[01 ATT&CK/DC0094 - Group Modification|DC0094 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Changes made to a group, such as membership, name, or permissions (ex: Windows EID 4728 or 4732, AWS IAM UpdateGroup). Examples: - Active Directory: - Event ID 4728: Member added to a global group. - Event ID 4732: Member added to a local group. - Azure AD: `Set-AzureADGroup -ObjectId -DisplayName "New Name"` - AWS IAM: `aws iam update-group --group-name --new-path "/admin/"` - Google Workspace: Modify permissions via Admin SDK API: `PATCH https://admin.googleapis.com/admin/directory/v1/groups/ ` - Office 365: Modify groups via Graph API: `PATCH https://graph.microsoft.com/v1.0/groups/ ` *Data Collection Measures:* - Directory Logging: - Windows: Log EIDs 4728 (add), 4729 (remove). - Azure AD: Enable "Audit logs." - Google Workspace: Enable Admin Activity logs. - Office 365: Use Unified Audit Logs. - Cloud Monitoring: - AWS: Log `UpdateGroup`, `AttachGroupPolicy`, `RemoveUserFromGroup`. - Azure: Track modifications via Audit logs. - API Monitoring: Log Google Admin SDK and Microsoft Graph API calls. - SIEM Integration: Centralize and monitor group modification logs.

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
