---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0069"
target_object: "T1070.004"
stix_relationship_id: "relationship--9fe01f98-e0b3-4749-b9a6-eb10c216c548"
---
# Relationship 5988: S0069 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0069 - BLACKCOFFEE|S0069: BLACKCOFFEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLACKCOFFEE](https://attack.mitre.org/software/S0069) has the capability to delete files.(Citation: FireEye APT17)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fe01f98-e0b3-4749-b9a6-eb10c216c548`.
