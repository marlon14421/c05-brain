---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0586"
target_object: "T1680"
stix_relationship_id: "relationship--e1eebea8-ad12-4c3f-bbdc-10f26bbccda8"
---
# Relationship 5810: S0586 — uses → T1680

**Source object:** [[01 ATT&CK/S0586 - TAINTEDSCRIBE|S0586: TAINTEDSCRIBE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TAINTEDSCRIBE](https://attack.mitre.org/software/S0586) can use DriveList to retrieve drive information.(Citation: CISA MAR-10288834-2.v1 TAINTEDSCRIBE MAY 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1eebea8-ad12-4c3f-bbdc-10f26bbccda8`.
