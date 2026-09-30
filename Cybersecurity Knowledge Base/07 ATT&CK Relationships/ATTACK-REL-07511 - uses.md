---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0093"
target_object: "T1070.004"
stix_relationship_id: "relationship--1d54c1d7-529f-4e4f-9a38-55b1b8cbff66"
---
# Relationship 7511: S0093 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0093 - Backdoor.Oldrea|S0093: Backdoor.Oldrea]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Backdoor.Oldrea](https://attack.mitre.org/software/S0093) contains a cleanup module that removes traces of itself from the victim.(Citation: Symantec Dragonfly)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d54c1d7-529f-4e4f-9a38-55b1b8cbff66`.
