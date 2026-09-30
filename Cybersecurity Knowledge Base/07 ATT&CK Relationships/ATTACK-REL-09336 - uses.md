---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1140"
stix_relationship_id: "relationship--d9e7b8b3-6275-4c26-b9d2-4adfa1143c1b"
---
# Relationship 9336: S0534 — uses → T1140

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bazar](https://attack.mitre.org/software/S0534) can decrypt downloaded payloads. [Bazar](https://attack.mitre.org/software/S0534) also resolves strings and other artifacts at runtime.(Citation: Cybereason Bazar July 2020)(Citation: NCC Group Team9 June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9e7b8b3-6275-4c26-b9d2-4adfa1143c1b`.
