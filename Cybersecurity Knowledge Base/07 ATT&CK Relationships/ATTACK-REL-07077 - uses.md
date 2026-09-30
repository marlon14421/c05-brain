---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1569.002"
stix_relationship_id: "relationship--6bbb4292-0496-412d-8277-af752703c46a"
---
# Relationship 7077: G1032 — uses → T1569.002

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has run a file encryption executable via `Service Control Manager/7045;winupd,%SystemRoot%\winupd.exe,user mode service,demand start,LocalSystem`.(Citation: Huntress INC Ransom Group August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6bbb4292-0496-412d-8277-af752703c46a`.
