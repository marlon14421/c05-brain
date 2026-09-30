---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1042"
target_object: "T1217"
stix_relationship_id: "relationship--a0020049-7688-4c0a-8844-dece3bed614c"
---
# Relationship 6449: S1042 — uses → T1217

**Source object:** [[01 ATT&CK/S1042 - SUGARDUMP|S1042: SUGARDUMP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUGARDUMP](https://attack.mitre.org/software/S1042) has collected browser bookmark and history information.(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0020049-7688-4c0a-8844-dece3bed614c`.
