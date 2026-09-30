---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0596"
target_object: "T1027.011"
stix_relationship_id: "relationship--4459b6fe-e1d0-40cb-b6f1-efc0e4431442"
---
# Relationship 9461: S0596 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShadowPad](https://attack.mitre.org/software/S0596) maintains a configuration block and virtual file system in the Registry.(Citation: Kaspersky ShadowPad Aug 2017)(Citation: TrendMicro EarthLusca 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4459b6fe-e1d0-40cb-b6f1-efc0e4431442`.
