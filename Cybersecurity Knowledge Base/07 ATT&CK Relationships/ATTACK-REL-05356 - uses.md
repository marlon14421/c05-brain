---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1480.002"
stix_relationship_id: "relationship--db52b791-ad42-45e5-b3be-5386c0d819f2"
---
# Relationship 5356: S1183 — uses → T1480.002

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) variants include the use of mutex values based on the victim system name to prevent reinfection.(Citation: Fortgale StrelaStealer 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db52b791-ad42-45e5-b3be-5386c0d819f2`.
