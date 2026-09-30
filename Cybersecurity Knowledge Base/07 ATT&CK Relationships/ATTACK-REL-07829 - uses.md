---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1202"
target_object: "T1027.002"
stix_relationship_id: "relationship--3570d377-9139-4221-9c4b-15147b78e8ad"
---
# Relationship 7829: S1202 — uses → T1027.002

**Source object:** [[01 ATT&CK/S1202 - LockBit 3.0|S1202: LockBit 3.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockBit 3.0](https://attack.mitre.org/software/S1202) can use code packing to hinder analysis.(Citation: Sentinel Labs LockBit 3.0 JUL 2022)(Citation: INCIBE-CERT LockBit MAR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3570d377-9139-4221-9c4b-15147b78e8ad`.
