---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1041"
target_object: "T1027.013"
stix_relationship_id: "relationship--af85b32a-7b5e-48ea-9777-50d4d625a122"
---
# Relationship 5335: S1041 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1041 - Chinoxy|S1041: Chinoxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chinoxy](https://attack.mitre.org/software/S1041) has encrypted its configuration file.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af85b32a-7b5e-48ea-9777-50d4d625a122`.
