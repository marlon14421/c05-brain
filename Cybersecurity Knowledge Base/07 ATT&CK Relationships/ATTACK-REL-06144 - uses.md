---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1248"
target_object: "T1027.010"
stix_relationship_id: "relationship--e7c4553f-442f-456f-82ee-9fdb6c6c7c40"
---
# Relationship 6144: S1248 — uses → T1027.010

**Source object:** [[01 ATT&CK/S1248 - XORIndex Loader|S1248: XORIndex Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XORIndex Loader](https://attack.mitre.org/software/S1248) has obfuscated strings using ASCII buffers and TextDecoder.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7c4553f-442f-456f-82ee-9fdb6c6c7c40`.
