---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1140"
stix_relationship_id: "relationship--959092cf-5647-4c25-b64e-3e84061511a5"
---
# Relationship 9869: S0240 — uses → T1140

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can decrypt strings using the victim's hostname as the key.(Citation: Volexity InkySquid RokRAT August 2021)(Citation: Malwarebytes RokRAT VBA January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--959092cf-5647-4c25-b64e-3e84061511a5`.
