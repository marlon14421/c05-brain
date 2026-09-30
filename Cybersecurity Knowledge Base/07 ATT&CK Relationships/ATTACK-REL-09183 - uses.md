---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1485"
stix_relationship_id: "relationship--1b996e11-03b7-48fc-9ce2-cd08fdf0d07d"
---
# Relationship 9183: G1004 — uses → T1485

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has deleted the target's systems and resources both on-premises and in the cloud.(Citation: MSTIC DEV-0537 Mar 2022)(Citation: NCC Group LAPSUS Apr 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b996e11-03b7-48fc-9ce2-cd08fdf0d07d`.
