---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "S0126"
stix_relationship_id: "relationship--35a9c64c-c305-46bf-a216-c8bb1b051614"
---
# Relationship 5700: G0010 — uses → S0126

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Waterbug)(Citation: Unit 42 IronNetInjector February 2021 )(Citation: Secureworks IRON HUNTER Profile)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35a9c64c-c305-46bf-a216-c8bb1b051614`.
