---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0083"
target_object: "T1070.004"
stix_relationship_id: "relationship--70a1cab8-dd98-4b82-9f7f-36294e3889c0"
---
# Relationship 6255: S0083 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0083 - Misdat|S0083: Misdat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Misdat](https://attack.mitre.org/software/S0083) is capable of deleting the backdoor file.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70a1cab8-dd98-4b82-9f7f-36294e3889c0`.
