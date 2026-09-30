---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1019"
target_object: "T1140"
stix_relationship_id: "relationship--b10f18a6-43a8-436f-8d9c-f180428f0a0d"
---
# Relationship 6741: S1019 — uses → T1140

**Source object:** [[01 ATT&CK/S1019 - Shark|S1019: Shark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shark](https://attack.mitre.org/software/S1019) can extract and decrypt downloaded .zip files.(Citation: ClearSky Siamesekitten August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b10f18a6-43a8-436f-8d9c-f180428f0a0d`.
