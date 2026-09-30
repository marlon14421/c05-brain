---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1047"
target_object: "T1083"
stix_relationship_id: "relationship--4d453252-ae9c-48c0-a9ab-2ca700855e3f"
---
# Relationship 9779: G1047 — uses → T1083

**Source object:** [[01 ATT&CK/G1047 - Velvet Ant|G1047: Velvet Ant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Velvet Ant](https://attack.mitre.org/groups/G1047) has enumerated local files and folders on victim devices.(Citation: Sygnia VelvetAnt 2024A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4d453252-ae9c-48c0-a9ab-2ca700855e3f`.
