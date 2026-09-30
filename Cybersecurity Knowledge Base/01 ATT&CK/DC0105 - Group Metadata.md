---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0105"
source_url: "https://attack.mitre.org/datacomponents/DC0105"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0105: Group Metadata

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0105  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Group metadata includes attributes like name, permissions, purpose, and associated user accounts or roles, which adversaries may exploit for privilege escalation. Examples: - Active Directory: `Get-ADGroup -Identity "Domain Admins" -Properties Members, Description` - Azure AD: `Get-AzureADGroup -ObjectId ` - Google Workspace: `GET https://admin.googleapis.com/admin/directory/v1/groups/ ` - AWS IAM: `aws iam list-group-policies --group-name ` - Office 365: `GET https://graph.microsoft.com/v1.0/groups/ ` *Data Collection Measures:* - Cloud Logging: - AWS CloudTrail for IAM group-related activities. - Azure AD Sign-In/Audit logs for metadata changes. - Google Admin Activity logs for API calls. - Directory Logging: Log metadata access (e.g., Windows Event ID 4662). - API Monitoring: Log API calls to modify group metadata (e.g., Microsoft Graph API). - SIEM Integration: Centralize group metadata logs for analysis.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0105](https://attack.mitre.org/datacomponents/DC0105)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
