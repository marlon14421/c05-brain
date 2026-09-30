---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1026"
target_object: "T1005"
stix_relationship_id: "relationship--86f238c5-20c2-4c94-9be9-886105c95252"
---
# Relationship 8734: S1026 — uses → T1005

**Source object:** [[01 ATT&CK/S1026 - Mongall|S1026: Mongall]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mongall](https://attack.mitre.org/software/S1026) has the ability to upload files from victim's machines.(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86f238c5-20c2-4c94-9be9-886105c95252`.
