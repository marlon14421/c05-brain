---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "S0192"
stix_relationship_id: "relationship--cde73e1c-da81-4673-a161-49693b45cd48"
---
# Relationship 9853: G0059 — uses → S0192

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Unit 42 Magic Hound Feb 2017)(Citation: FireEye APT35 2018)(Citation: Secureworks Cobalt Gypsy Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cde73e1c-da81-4673-a161-49693b45cd48`.
