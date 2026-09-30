---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1070.004"
stix_relationship_id: "relationship--504b0048-f6a6-4cb2-bf72-6f2997c7a931"
---
# Relationship 5490: S1239 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has deleted payload files received from the C2 server.(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--504b0048-f6a6-4cb2-bf72-6f2997c7a931`.
