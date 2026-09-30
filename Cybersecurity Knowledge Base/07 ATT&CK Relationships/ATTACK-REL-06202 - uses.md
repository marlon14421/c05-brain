---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0130"
target_object: "T1091"
stix_relationship_id: "relationship--291df761-474b-4c5f-a9bd-2aaef0f80d70"
---
# Relationship 6202: S0130 — uses → T1091

**Source object:** [[01 ATT&CK/S0130 - Unknown Logger|S0130: Unknown Logger]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Unknown Logger](https://attack.mitre.org/software/S0130) is capable of spreading to USB devices.(Citation: Forcepoint Monsoon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--291df761-474b-4c5f-a9bd-2aaef0f80d70`.
