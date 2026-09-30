---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1028"
target_object: "T1140"
stix_relationship_id: "relationship--0303acd0-64a4-4e40-b8e3-29e1c43694d2"
---
# Relationship 9288: S1028 — uses → T1140

**Source object:** [[01 ATT&CK/S1028 - Action RAT|S1028: Action RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Action RAT](https://attack.mitre.org/software/S1028) can use Base64 to decode actor-controlled C2 server communications.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0303acd0-64a4-4e40-b8e3-29e1c43694d2`.
