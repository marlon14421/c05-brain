---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1480.002"
stix_relationship_id: "relationship--dba52e3c-fb05-4001-9fa4-39d4cd673ad0"
---
# Relationship 9866: G0094 — uses → T1480.002

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has utilized a mutex to detect whether its malware is actively running on the victim host.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has leveraged PowerShell to store the Process ID (PID) of the currently running malicious PowerShell script into a file named pid.txt which is saved locally on the victim host in the %TEMP% Directory and is queried prior to execution of subsequent PowerShell script to prevent duplication.(Citation: Aryaka Kimsuky July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dba52e3c-fb05-4001-9fa4-39d4cd673ad0`.
