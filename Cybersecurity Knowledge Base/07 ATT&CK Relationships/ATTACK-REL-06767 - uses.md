---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1027"
stix_relationship_id: "relationship--3979ca39-09a1-4a2b-a7d3-2eca5f1fb166"
---
# Relationship 6767: S1086 — uses → T1027

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) has the ability to obfuscate strings using XOR encryption.(Citation: Morphisec Snip3 May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3979ca39-09a1-4a2b-a7d3-2eca5f1fb166`.
