---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0126"
target_object: "T1140"
stix_relationship_id: "relationship--fa22812f-01a4-420a-be11-7cb5822026e5"
---
# Relationship 9587: G0126 — uses → T1140

**Source object:** [[01 ATT&CK/G0126 - Higaisa|G0126: Higaisa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Higaisa](https://attack.mitre.org/groups/G0126) used certutil to decode Base64 binaries at runtime and a 16-byte XOR key to decrypt data.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa22812f-01a4-420a-be11-7cb5822026e5`.
