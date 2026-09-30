---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1123"
target_object: "T1140"
stix_relationship_id: "relationship--e7caa3b3-78d3-4840-bee3-70d7637f5508"
---
# Relationship 5649: S1123 — uses → T1140

**Source object:** [[01 ATT&CK/S1123 - PITSTOP|S1123: PITSTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PITSTOP](https://attack.mitre.org/software/S1123) can deobfuscate base64 encoded and AES encrypted commands.(Citation: Mandiant Cutting Edge Part 3 February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7caa3b3-78d3-4840-bee3-70d7637f5508`.
