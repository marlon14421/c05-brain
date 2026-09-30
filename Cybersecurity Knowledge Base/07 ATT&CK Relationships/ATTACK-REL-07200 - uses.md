---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1153"
target_object: "T1518"
stix_relationship_id: "relationship--2cfb6d2b-5a32-4ff9-9eb8-83a051eaff0d"
---
# Relationship 7200: S1153 — uses → T1518

**Source object:** [[01 ATT&CK/S1153 - Cuckoo Stealer|S1153: Cuckoo Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cuckoo Stealer](https://attack.mitre.org/software/S1153) has the ability to search systems for installed applications.(Citation: Kandji Cuckoo April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2cfb6d2b-5a32-4ff9-9eb8-83a051eaff0d`.
