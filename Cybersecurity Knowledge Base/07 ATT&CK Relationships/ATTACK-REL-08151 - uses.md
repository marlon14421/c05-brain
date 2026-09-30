---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0608"
target_object: "T1568.002"
stix_relationship_id: "relationship--98339175-97d1-4a17-985f-914efffa2a4e"
---
# Relationship 8151: S0608 — uses → T1568.002

**Source object:** [[01 ATT&CK/S0608 - Conficker|S0608: Conficker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.002 - Domain Generation Algorithms|T1568.002: Domain Generation Algorithms]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conficker](https://attack.mitre.org/software/S0608) has used a DGA that seeds with the current UTC victim system date to generate domains.(Citation: SANS Conficker)(Citation: Trend Micro Conficker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98339175-97d1-4a17-985f-914efffa2a4e`.
