---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1027.013"
stix_relationship_id: "relationship--5f8c7f7a-14e2-44d2-a2d8-d37b00134aa9"
---
# Relationship 8193: S1185 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightSpy](https://attack.mitre.org/software/S1185) encrypts the C2 configuration file using AES with a static key, while the module `.dylib` files use a rolling one-byte encoding for obfuscation.(Citation: Huntress LightSpy macOS 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f8c7f7a-14e2-44d2-a2d8-d37b00134aa9`.
