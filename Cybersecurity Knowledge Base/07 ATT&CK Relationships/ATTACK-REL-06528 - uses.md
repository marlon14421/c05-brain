---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0088"
target_object: "T1082"
stix_relationship_id: "relationship--49af09c8-1460-485d-9f09-dacea47fa016"
---
# Relationship 6528: S0088 — uses → T1082

**Source object:** [[01 ATT&CK/S0088 - Kasidet|S0088: Kasidet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kasidet](https://attack.mitre.org/software/S0088) has the ability to obtain a victim's system name and operating system version.(Citation: Zscaler Kasidet)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49af09c8-1460-485d-9f09-dacea47fa016`.
