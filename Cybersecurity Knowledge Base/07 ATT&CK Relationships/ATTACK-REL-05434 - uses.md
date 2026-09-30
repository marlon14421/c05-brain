---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0565"
target_object: "T1140"
stix_relationship_id: "relationship--ff10b414-cc17-4335-9030-1262e5401b39"
---
# Relationship 5434: S0565 — uses → T1140

**Source object:** [[01 ATT&CK/S0565 - Raindrop|S0565: Raindrop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raindrop](https://attack.mitre.org/software/S0565) decrypted its [Cobalt Strike](https://attack.mitre.org/software/S0154) payload using an AES-256 encryption algorithm in CBC mode with a unique key per sample.(Citation: Symantec RAINDROP January 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff10b414-cc17-4335-9030-1262e5401b39`.
