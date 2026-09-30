---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1030"
target_object: "T1016"
stix_relationship_id: "relationship--fe83c4f7-7a52-4a4f-8d17-a28e0ca162ed"
---
# Relationship 7844: S1030 — uses → T1016

**Source object:** [[01 ATT&CK/S1030 - Squirrelwaffle|S1030: Squirrelwaffle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Squirrelwaffle](https://attack.mitre.org/software/S1030) has collected the victim’s external IP address.(Citation: ZScaler Squirrelwaffle Sep 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe83c4f7-7a52-4a4f-8d17-a28e0ca162ed`.
