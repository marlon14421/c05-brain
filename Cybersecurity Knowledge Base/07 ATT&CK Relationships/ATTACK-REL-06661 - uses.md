---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1202"
target_object: "T1140"
stix_relationship_id: "relationship--0805f7ac-0596-4154-bf56-8eb0ee5cc635"
---
# Relationship 6661: S1202 — uses → T1140

**Source object:** [[01 ATT&CK/S1202 - LockBit 3.0|S1202: LockBit 3.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [LockBit 3.0](https://attack.mitre.org/software/S1202) payload is decrypted at runtime.(Citation: Sentinel Labs LockBit 3.0 JUL 2022)(Citation: Joint Cybersecurity Advisory LockBit 3.0 MAR 2023)(Citation: INCIBE-CERT LockBit MAR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0805f7ac-0596-4154-bf56-8eb0ee5cc635`.
