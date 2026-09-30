---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0448"
target_object: "T1680"
stix_relationship_id: "relationship--f87c6571-5031-4abb-8eaf-3416eec79928"
---
# Relationship 5557: S0448 — uses → T1680

**Source object:** [[01 ATT&CK/S0448 - Rising Sun|S0448: Rising Sun]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rising Sun](https://attack.mitre.org/software/S0448) can detect drive information, including drive type, total number of bytes on disk, total number of free bytes on disk, and name of a specified volume.(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f87c6571-5031-4abb-8eaf-3416eec79928`.
