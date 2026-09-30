---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1044"
target_object: "T1025"
stix_relationship_id: "relationship--e6e4cb23-3c58-41d8-9583-9e10bff2b1d0"
---
# Relationship 8264: S1044 — uses → T1025

**Source object:** [[01 ATT&CK/S1044 - FunnyDream|S1044: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [FunnyDream](https://attack.mitre.org/software/S1044) FilePakMonitor component has the ability to collect files from removable devices.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6e4cb23-3c58-41d8-9583-9e10bff2b1d0`.
