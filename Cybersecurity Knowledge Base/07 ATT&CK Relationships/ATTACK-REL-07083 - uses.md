---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1041"
target_object: "T1140"
stix_relationship_id: "relationship--356aa4b0-e6c2-4ef7-a3b2-837c25c283b3"
---
# Relationship 7083: S1041 — uses → T1140

**Source object:** [[01 ATT&CK/S1041 - Chinoxy|S1041: Chinoxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Chinoxy](https://attack.mitre.org/software/S1041) dropping function can initiate decryption of its config file.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--356aa4b0-e6c2-4ef7-a3b2-837c25c283b3`.
