---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0380"
target_object: "T1113"
stix_relationship_id: "relationship--f097324d-6665-4d2d-8d84-eb05bada0dd3"
---
# Relationship 8551: S0380 — uses → T1113

**Source object:** [[01 ATT&CK/S0380 - StoneDrill|S0380: StoneDrill]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StoneDrill](https://attack.mitre.org/software/S0380) can take screenshots.(Citation: Kaspersky StoneDrill 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f097324d-6665-4d2d-8d84-eb05bada0dd3`.
