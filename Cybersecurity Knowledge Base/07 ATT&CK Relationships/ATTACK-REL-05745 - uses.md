---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0596"
target_object: "T1124"
stix_relationship_id: "relationship--088c3553-db7f-4e97-9f32-75e483d59cba"
---
# Relationship 5745: S0596 — uses → T1124

**Source object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShadowPad](https://attack.mitre.org/software/S0596) has collected the current date and time of the victim system.(Citation: Kaspersky ShadowPad Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--088c3553-db7f-4e97-9f32-75e483d59cba`.
