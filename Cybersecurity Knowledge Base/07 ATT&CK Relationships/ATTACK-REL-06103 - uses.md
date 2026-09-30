---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0216"
target_object: "T1113"
stix_relationship_id: "relationship--4e2f4bbd-ea3b-4996-bc2a-3d670d9f5cf5"
---
# Relationship 6103: S0216 — uses → T1113

**Source object:** [[01 ATT&CK/S0216 - POORAIM|S0216: POORAIM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POORAIM](https://attack.mitre.org/software/S0216) can perform screen capturing.(Citation: FireEye APT37 Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e2f4bbd-ea3b-4996-bc2a-3d670d9f5cf5`.
