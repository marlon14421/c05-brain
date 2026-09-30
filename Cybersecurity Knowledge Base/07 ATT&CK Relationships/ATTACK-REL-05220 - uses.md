---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0213"
target_object: "T1056.001"
stix_relationship_id: "relationship--52278e18-f8b3-4bf1-a5d3-ac819ccfd301"
---
# Relationship 5220: S0213 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0213 - DOGCALL|S0213: DOGCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DOGCALL](https://attack.mitre.org/software/S0213) is capable of logging keystrokes.(Citation: FireEye APT37 Feb 2018)(Citation: Unit 42 Nokki Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52278e18-f8b3-4bf1-a5d3-ac819ccfd301`.
