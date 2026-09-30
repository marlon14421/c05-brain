---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0342"
target_object: "T1070.004"
stix_relationship_id: "relationship--1ae53b90-59d3-4510-b0e8-686b7ea8e626"
---
# Relationship 8015: S0342 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0342 - GreyEnergy|S0342: GreyEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GreyEnergy](https://attack.mitre.org/software/S0342) can securely delete a file by hooking into the DeleteFileA and DeleteFileW functions in the Windows API.(Citation: ESET GreyEnergy Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ae53b90-59d3-4510-b0e8-686b7ea8e626`.
