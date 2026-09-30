---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1485"
stix_relationship_id: "relationship--4b4ac061-dee5-44f3-b0f5-021889eae45e"
---
# Relationship 5495: S0140 — uses → T1485

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) attempts to overwrite operating system files and disk structures with image files.(Citation: Symantec Shamoon 2012)(Citation: FireEye Shamoon Nov 2016)(Citation: Palo Alto Shamoon Nov 2016) In a later variant, randomly generated data was used for data overwrites.(Citation: Unit 42 Shamoon3 2018)(Citation: McAfee Shamoon December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b4ac061-dee5-44f3-b0f5-021889eae45e`.
