---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1008"
target_object: "T1059.005"
stix_relationship_id: "relationship--86bfc0ee-73e0-4f1b-a4f9-f8e44eae2dc3"
---
# Relationship 8324: G1008 — uses → T1059.005

**Source object:** [[01 ATT&CK/G1008 - SideCopy|G1008: SideCopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SideCopy](https://attack.mitre.org/groups/G1008) has sent Microsoft Office Publisher documents to victims that have embedded malicious macros that execute an hta file via calling `mshta.exe`.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86bfc0ee-73e0-4f1b-a4f9-f8e44eae2dc3`.
