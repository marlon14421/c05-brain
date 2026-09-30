---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0565"
target_object: "T1027.013"
stix_relationship_id: "relationship--03cd94c9-73aa-4eed-b724-629d180e3002"
---
# Relationship 8875: S0565 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0565 - Raindrop|S0565: Raindrop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raindrop](https://attack.mitre.org/software/S0565) encrypted its payload using a simple XOR algorithm with a single-byte key.(Citation: Symantec RAINDROP January 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03cd94c9-73aa-4eed-b724-629d180e3002`.
