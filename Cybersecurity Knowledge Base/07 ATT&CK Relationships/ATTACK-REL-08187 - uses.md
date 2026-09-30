---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1070.004"
stix_relationship_id: "relationship--0741e02b-edaa-43a4-a96c-d6baf2d29015"
---
# Relationship 8187: G0045 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [menuPass](https://attack.mitre.org/groups/G0045) macro deletes files after it has decoded and decompressed them.(Citation: Accenture Hogfish April 2018)(Citation: District Court of NY APT10 Indictment December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0741e02b-edaa-43a4-a96c-d6baf2d29015`.
