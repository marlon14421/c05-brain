---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1027.013"
stix_relationship_id: "relationship--bc9a5286-98a6-4905-b4ce-8f4d958861b6"
---
# Relationship 9008: S0330 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) encrypts strings with XOR. [Zeus Panda](https://attack.mitre.org/software/S0330) also encrypts all configuration and settings in AES and RC4.(Citation: Talos Zeus Panda Nov 2017)(Citation: GDATA Zeus Panda June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc9a5286-98a6-4905-b4ce-8f4d958861b6`.
