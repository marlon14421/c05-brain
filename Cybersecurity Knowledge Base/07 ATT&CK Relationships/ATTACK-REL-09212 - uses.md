---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0468"
target_object: "T1027.013"
stix_relationship_id: "relationship--2329d963-f01b-46bd-8868-99cf436a508a"
---
# Relationship 9212: S0468 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0468 - Skidmap|S0468: Skidmap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Skidmap](https://attack.mitre.org/software/S0468) has encrypted it's main payload using 3DES.(Citation: Trend Micro Skidmap)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2329d963-f01b-46bd-8868-99cf436a508a`.
