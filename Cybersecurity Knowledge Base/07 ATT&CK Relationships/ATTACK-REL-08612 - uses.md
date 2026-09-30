---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0020"
target_object: "T1046"
stix_relationship_id: "relationship--73ce71e3-938e-4f5e-b588-32426e874577"
---
# Relationship 8612: S0020 — uses → T1046

**Source object:** [[01 ATT&CK/S0020 - China Chopper|S0020: China Chopper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[China Chopper](https://attack.mitre.org/software/S0020)'s server component can spider authentication portals.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73ce71e3-938e-4f5e-b588-32426e874577`.
