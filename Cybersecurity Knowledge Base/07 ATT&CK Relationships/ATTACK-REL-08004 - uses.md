---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1043"
target_object: "T1124"
stix_relationship_id: "relationship--3881653b-bd16-4eba-ab35-81da1872c5c8"
---
# Relationship 8004: S1043 — uses → T1124

**Source object:** [[01 ATT&CK/S1043 - ccf32|S1043: ccf32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ccf32](https://attack.mitre.org/software/S1043) can determine the local time on targeted machines.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3881653b-bd16-4eba-ab35-81da1872c5c8`.
