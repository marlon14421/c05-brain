---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1235"
target_object: "T1553.002"
stix_relationship_id: "relationship--0d8106ed-7d52-40bc-be54-5c8c6bc9f0f5"
---
# Relationship 6796: S1235 — uses → T1553.002

**Source object:** [[01 ATT&CK/S1235 - CorKLOG|S1235: CorKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CorKLOG](https://attack.mitre.org/software/S1235) has used legitimate signed binaries such as lcommute.exe for follow-on execution of malicious DLLs through DLL side-loading.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d8106ed-7d52-40bc-be54-5c8c6bc9f0f5`.
