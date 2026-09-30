---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1134"
target_object: "T1140"
stix_relationship_id: "relationship--a91a486b-4119-44e1-9fcf-c746849947e8"
---
# Relationship 7705: S1134 — uses → T1140

**Source object:** [[01 ATT&CK/S1134 - DEADWOOD|S1134: DEADWOOD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEADWOOD](https://attack.mitre.org/software/S1134) XORs some strings within the binary using the value 0xD5 , and deobfuscates these items at runtime.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a91a486b-4119-44e1-9fcf-c746849947e8`.
