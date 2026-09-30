---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1139"
target_object: "T1047"
stix_relationship_id: "relationship--5e0bb60b-21e7-4913-862b-61f8831c1732"
---
# Relationship 6260: S1139 — uses → T1047

**Source object:** [[01 ATT&CK/S1139 - INC Ransomware|S1139: INC Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransomware](https://attack.mitre.org/software/S1139) has the ability to use wmic.exe to spread to multiple endpoints within a compromised environment.(Citation: Huntress INC Ransom Group August 2023)(Citation: Secureworks GOLD IONIC April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e0bb60b-21e7-4913-862b-61f8831c1732`.
