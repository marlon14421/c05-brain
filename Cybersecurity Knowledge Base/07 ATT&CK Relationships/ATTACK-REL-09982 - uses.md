---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9011"
target_object: "T1140"
stix_relationship_id: "relationship--3cadf7f7-481c-45e4-b64b-ed03b349be20"
---
# Relationship 9982: S9011 — uses → T1140

**Source object:** [[01 ATT&CK/S9011 - BRUSHFIRE|S9011: BRUSHFIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRUSHFIRE](https://attack.mitre.org/software/S9011) has decrypted XOR strings prior to execution.(Citation: Google UNC5221 Ivanti April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cadf7f7-481c-45e4-b64b-ed03b349be20`.
