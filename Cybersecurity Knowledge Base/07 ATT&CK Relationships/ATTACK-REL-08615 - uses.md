---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0139"
target_object: "T1485"
stix_relationship_id: "relationship--5135ba35-04b7-4cfc-bc6c-03f63206e757"
---
# Relationship 8615: S0139 — uses → T1485

**Source object:** [[01 ATT&CK/S0139 - PowerDuke|S0139: PowerDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerDuke](https://attack.mitre.org/software/S0139) has a command to write random data across a file and delete it.(Citation: Volexity PowerDuke November 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5135ba35-04b7-4cfc-bc6c-03f63206e757`.
