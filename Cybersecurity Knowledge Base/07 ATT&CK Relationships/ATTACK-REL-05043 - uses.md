---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0495"
target_object: "T1008"
stix_relationship_id: "relationship--d96db78c-e7b8-4877-8187-07c5e801cead"
---
# Relationship 5043: S0495 — uses → T1008

**Source object:** [[01 ATT&CK/S0495 - RDAT|S0495: RDAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RDAT](https://attack.mitre.org/software/S0495) has used HTTP if DNS C2 communications were not functioning.(Citation: Unit42 RDAT July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d96db78c-e7b8-4877-8187-07c5e801cead`.
