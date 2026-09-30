---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1083"
stix_relationship_id: "relationship--91e69232-941e-43bf-9f10-b0e4cf8b43d1"
---
# Relationship 7519: S1130 — uses → T1083

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) will check to see if the initial executing script is located on the user's Desktop as an anti-analysis check.(Citation: HP RaspberryRobin 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91e69232-941e-43bf-9f10-b0e4cf8b43d1`.
