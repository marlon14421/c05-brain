---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0081"
target_object: "T1564.001"
stix_relationship_id: "relationship--4269342d-fd7b-4fc6-882f-5099da627c85"
---
# Relationship 6546: G0081 — uses → T1564.001

**Source object:** [[01 ATT&CK/G0081 - Tropic Trooper|G0081: Tropic Trooper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tropic Trooper](https://attack.mitre.org/groups/G0081) has created a hidden directory under C:\ProgramData\Apple\Updates\ and C:\Users\Public\Documents\Flash\ .(Citation: TrendMicro Tropic Trooper Mar 2018)(Citation: TrendMicro Tropic Trooper May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4269342d-fd7b-4fc6-882f-5099da627c85`.
