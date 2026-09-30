---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0344"
target_object: "T1070.004"
stix_relationship_id: "relationship--0f785fc5-0d07-40bd-8d54-acfb79499824"
---
# Relationship 9953: S0344 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0344 - Azorult|S0344: Azorult]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Azorult](https://attack.mitre.org/software/S0344) can delete files from victim machines.(Citation: Unit42 Azorult Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f785fc5-0d07-40bd-8d54-acfb79499824`.
