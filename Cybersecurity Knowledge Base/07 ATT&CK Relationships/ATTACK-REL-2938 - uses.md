---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1005"
stix_relationship_id: "relationship--fcef9b21-8ad5-4c9d-bb04-a5db2053a223"
---
# Relationship 2938: C0058 — uses → T1005

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors extracted information from the compromised systems.(Citation: Microsoft SharePoint Exploit JUL 2025)(Citation: ESET ToolShell JUL 2025)(Citation: SentinelOne ToolShell JUL 2025)(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fcef9b21-8ad5-4c9d-bb04-a5db2053a223`.
