---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1497.003"
stix_relationship_id: "relationship--1fb2a0f2-5d60-4b72-9d18-5d5d06d0c2fe"
---
# Relationship 7184: S0611 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clop](https://attack.mitre.org/software/S0611) has used the sleep command to avoid sandbox detection.(Citation: Unit42 Clop April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1fb2a0f2-5d60-4b72-9d18-5d5d06d0c2fe`.
