---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1248"
target_object: "T1027.013"
stix_relationship_id: "relationship--cd0cc9b2-516b-4674-8b4d-798204ffe49e"
---
# Relationship 9567: S1248 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1248 - XORIndex Loader|S1248: XORIndex Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XORIndex Loader](https://attack.mitre.org/software/S1248) has encoded module names and C2 URLs as hexadecimal strings in attempts to evade analysis.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd0cc9b2-516b-4674-8b4d-798204ffe49e`.
