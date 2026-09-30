---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1574"
stix_relationship_id: "relationship--3270c057-e0ee-4a0c-a503-cad4782b6dc2"
---
# Relationship 8864: S9024 — uses → T1574

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) can persist across system upgrades by hijacking the execution flow of dspkginstall, a binary used during the system upgrade process.(Citation: Google UNC5221 Ivanti January 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3270c057-e0ee-4a0c-a503-cad4782b6dc2`.
