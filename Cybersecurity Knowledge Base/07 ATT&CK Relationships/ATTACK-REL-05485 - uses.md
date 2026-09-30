---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1518.001"
stix_relationship_id: "relationship--37d43abb-78c6-45b7-927d-353f5f95c322"
---
# Relationship 5485: S9024 — uses → T1518.001

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has checked where SELinux is enabled on the targeted host.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37d43abb-78c6-45b7-927d-353f5f95c322`.
