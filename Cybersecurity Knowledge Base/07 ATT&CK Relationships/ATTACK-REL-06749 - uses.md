---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1029"
target_object: "T1033"
stix_relationship_id: "relationship--1f5efc33-a643-4f9b-aae9-6c59208ff790"
---
# Relationship 6749: S1029 — uses → T1033

**Source object:** [[01 ATT&CK/S1029 - AuTo Stealer|S1029: AuTo Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AuTo Stealer](https://attack.mitre.org/software/S1029) has the ability to collect the username from an infected host.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f5efc33-a643-4f9b-aae9-6c59208ff790`.
