---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0035"
target_object: "T1560.003"
stix_relationship_id: "relationship--23df6015-0167-481c-84aa-3d15d3e38a85"
---
# Relationship 9620: S0035 — uses → T1560.003

**Source object:** [[01 ATT&CK/S0035 - SPACESHIP|S0035: SPACESHIP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Data [SPACESHIP](https://attack.mitre.org/software/S0035) copies to the staging area is compressed with zlib. Bytes are rotated by four positions and XOR'ed with 0x23.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23df6015-0167-481c-84aa-3d15d3e38a85`.
