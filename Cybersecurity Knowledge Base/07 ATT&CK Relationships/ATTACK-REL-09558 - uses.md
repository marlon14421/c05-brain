---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0142"
target_object: "T1083"
stix_relationship_id: "relationship--c8b0afbb-12eb-4b45-a1e1-b11755de2976"
---
# Relationship 9558: S0142 — uses → T1083

**Source object:** [[01 ATT&CK/S0142 - StreamEx|S0142: StreamEx]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StreamEx](https://attack.mitre.org/software/S0142) has the ability to enumerate drive types.(Citation: Cylance Shell Crew Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8b0afbb-12eb-4b45-a1e1-b11755de2976`.
