---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0265"
target_object: "T1016"
stix_relationship_id: "relationship--e534bf54-5f9f-4d5f-bd9d-260e56da4951"
---
# Relationship 9613: S0265 — uses → T1016

**Source object:** [[01 ATT&CK/S0265 - Kazuar|S0265: Kazuar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kazuar](https://attack.mitre.org/software/S0265) gathers information about network adapters.(Citation: Unit 42 Kazuar May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e534bf54-5f9f-4d5f-bd9d-260e56da4951`.
