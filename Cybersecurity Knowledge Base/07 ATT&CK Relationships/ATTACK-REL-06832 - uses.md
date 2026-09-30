---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0062"
target_object: "T1518"
stix_relationship_id: "relationship--2b89f806-5b78-4599-9536-13b47c35d26d"
---
# Relationship 6832: S0062 — uses → T1518

**Source object:** [[01 ATT&CK/S0062 - DustySky|S0062: DustySky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DustySky](https://attack.mitre.org/software/S0062) lists all installed software for the infected machine.(Citation: Kaspersky MoleRATs April 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b89f806-5b78-4599-9536-13b47c35d26d`.
