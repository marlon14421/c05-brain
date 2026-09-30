---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1188"
target_object: "T1505.003"
stix_relationship_id: "relationship--acf24e0b-9d44-4320-bfd3-3d9e4fc1a3c8"
---
# Relationship 5410: S1188 — uses → T1505.003

**Source object:** [[01 ATT&CK/S1188 - Line Runner|S1188: Line Runner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Line Runner](https://attack.mitre.org/software/S1188) is a persistent Lua-based web shell.(Citation: CCCS ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--acf24e0b-9d44-4320-bfd3-3d9e4fc1a3c8`.
