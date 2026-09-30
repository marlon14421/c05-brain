---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0083"
target_object: "T1106"
stix_relationship_id: "relationship--fdd7f2b3-08e4-4f55-ba94-4b5e6d619da8"
---
# Relationship 9790: S0083 — uses → T1106

**Source object:** [[01 ATT&CK/S0083 - Misdat|S0083: Misdat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Misdat](https://attack.mitre.org/software/S0083) has used Windows APIs, including `ExitWindowsEx` and `GetKeyboardType`.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdd7f2b3-08e4-4f55-ba94-4b5e6d619da8`.
