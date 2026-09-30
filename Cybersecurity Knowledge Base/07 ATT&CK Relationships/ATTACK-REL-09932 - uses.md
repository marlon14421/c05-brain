---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0060"
target_object: "T1070.004"
stix_relationship_id: "relationship--6affe529-57fa-43f5-9ab8-6b59209dc74f"
---
# Relationship 9932: C0060 — uses → T1070.004

**Source object:** [[01 ATT&CK/C0060 - Operation AkaiRyū|C0060: Operation AkaiRyū]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation AkaiRyū](https://attack.mitre.org/campaigns/C0060), [MirrorFace](https://attack.mitre.org/groups/G1054) deleted delivered tools and files from compromised hosts.(Citation: ESET MirrorFace 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6affe529-57fa-43f5-9ab8-6b59209dc74f`.
