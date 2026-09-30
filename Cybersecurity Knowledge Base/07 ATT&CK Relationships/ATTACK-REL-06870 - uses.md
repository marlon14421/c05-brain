---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1023"
target_object: "T1083"
stix_relationship_id: "relationship--95a8788a-b36c-4234-94bc-951eb1f72cce"
---
# Relationship 6870: S1023 — uses → T1083

**Source object:** [[01 ATT&CK/S1023 - CreepyDrive|S1023: CreepyDrive]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CreepyDrive](https://attack.mitre.org/software/S1023) can specify the local file path to upload files from.(Citation: Microsoft POLONIUM June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95a8788a-b36c-4234-94bc-951eb1f72cce`.
