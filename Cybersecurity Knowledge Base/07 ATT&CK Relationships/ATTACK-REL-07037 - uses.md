---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1091"
stix_relationship_id: "relationship--fc0432e9-1b49-4be8-b86e-15cdec6b070e"
---
# Relationship 7037: S0386 — uses → T1091

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has copied itself to and infected removable drives for propagation.(Citation: TrendMicro Ursnif Mar 2015)(Citation: TrendMicro Ursnif File Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc0432e9-1b49-4be8-b86e-15cdec6b070e`.
