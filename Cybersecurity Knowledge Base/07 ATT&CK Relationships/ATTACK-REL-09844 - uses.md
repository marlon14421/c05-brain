---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1012"
target_object: "T1005"
stix_relationship_id: "relationship--543dd290-70eb-402f-8d40-93b4a240d4a1"
---
# Relationship 9844: S1012 — uses → T1005

**Source object:** [[01 ATT&CK/S1012 - PowerLess|S1012: PowerLess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerLess](https://attack.mitre.org/software/S1012) has the ability to exfiltrate data, including Chrome and Edge browser database files, from compromised machines.(Citation: Cybereason PowerLess February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--543dd290-70eb-402f-8d40-93b4a240d4a1`.
