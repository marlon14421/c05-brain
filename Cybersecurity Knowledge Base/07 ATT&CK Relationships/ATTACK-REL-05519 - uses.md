---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0517"
target_object: "T1140"
stix_relationship_id: "relationship--abece522-51dc-4904-b0f9-585db7fb0223"
---
# Relationship 5519: S0517 — uses → T1140

**Source object:** [[01 ATT&CK/S0517 - Pillowmint|S0517: Pillowmint]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pillowmint](https://attack.mitre.org/software/S0517) has been decompressed by included shellcode prior to being launched.(Citation: Trustwave Pillowmint June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abece522-51dc-4904-b0f9-585db7fb0223`.
