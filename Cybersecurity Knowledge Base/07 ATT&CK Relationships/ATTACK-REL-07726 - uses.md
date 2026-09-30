---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1012"
target_object: "T1059.001"
stix_relationship_id: "relationship--c001d2e1-0aa6-40ce-871e-5966199587cd"
---
# Relationship 7726: S1012 — uses → T1059.001

**Source object:** [[01 ATT&CK/S1012 - PowerLess|S1012: PowerLess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerLess](https://attack.mitre.org/software/S1012) is written in and executed via PowerShell without using powershell.exe.(Citation: Cybereason PowerLess February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c001d2e1-0aa6-40ce-871e-5966199587cd`.
