---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1105"
stix_relationship_id: "relationship--e9384783-49a9-4ef0-89e7-aa2f94f389df"
---
# Relationship 5010: C0058 — uses → T1105

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors used a loader to download and execute ransomware.(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9384783-49a9-4ef0-89e7-aa2f94f389df`.
