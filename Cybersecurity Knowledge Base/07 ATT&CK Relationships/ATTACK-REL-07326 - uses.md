---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0615"
target_object: "T1140"
stix_relationship_id: "relationship--21281614-d7cc-4211-9365-d318c99cb906"
---
# Relationship 7326: S0615 — uses → T1140

**Source object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SombRAT](https://attack.mitre.org/software/S0615) can run upload to decrypt and upload files from storage.(Citation: BlackBerry CostaRicto November 2020)(Citation: CISA AR21-126A FIVEHANDS May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21281614-d7cc-4211-9365-d318c99cb906`.
