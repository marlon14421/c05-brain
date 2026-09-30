---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "S0157"
stix_relationship_id: "relationship--55f58d30-b633-4094-97bb-6ab872c0f480"
---
# Relationship 6192: G0050 — uses → S0157

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0157 - SOUNDBITE|S0157: SOUNDBITE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye APT32 May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55f58d30-b633-4094-97bb-6ab872c0f480`.
