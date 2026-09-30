---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0493"
target_object: "T1070.004"
stix_relationship_id: "relationship--8c2a7700-2054-4db1-b566-391f23a9f30a"
---
# Relationship 8899: S0493 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0493 - GoldenSpy|S0493: GoldenSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoldenSpy](https://attack.mitre.org/software/S0493)'s uninstaller can delete registry entries, files and folders, and finally itself once these tasks have been completed.(Citation: Trustwave GoldenSpy2 June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c2a7700-2054-4db1-b566-391f23a9f30a`.
