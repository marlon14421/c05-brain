---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0053"
target_object: "T1070.004"
stix_relationship_id: "relationship--6f8cef32-d057-40f8-be52-62d86b1049e6"
---
# Relationship 9504: S0053 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0053 - SeaDuke|S0053: SeaDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SeaDuke](https://attack.mitre.org/software/S0053) can securely delete files, including deleting itself from the victim.(Citation: Symantec Seaduke 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6f8cef32-d057-40f8-be52-62d86b1049e6`.
