---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0612"
target_object: "T1140"
stix_relationship_id: "relationship--c9ebddf7-337f-4002-84fd-84a7744b78e1"
---
# Relationship 9821: S0612 — uses → T1140

**Source object:** [[01 ATT&CK/S0612 - WastedLocker|S0612: WastedLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WastedLocker](https://attack.mitre.org/software/S0612)'s custom cryptor, CryptOne, used an XOR based algorithm to decrypt the payload.(Citation: NCC Group WastedLocker June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9ebddf7-337f-4002-84fd-84a7744b78e1`.
