---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1559"
stix_relationship_id: "relationship--a65e797a-d529-427b-82aa-33edf4ead0a2"
---
# Relationship 9310: S9024 — uses → T1559

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has leveraged IPC using a UNIX domain socket between the dsmdm process and the web process.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: JPCERT SPAWNCHIMERA Ivanti February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a65e797a-d529-427b-82aa-33edf4ead0a2`.
