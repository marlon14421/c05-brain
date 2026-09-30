---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0168"
target_object: "T1027.013"
stix_relationship_id: "relationship--deb7df24-689e-4e4e-909f-a270241ab65a"
---
# Relationship 9129: S0168 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0168 - Gazer|S0168: Gazer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gazer](https://attack.mitre.org/software/S0168) logs its actions into files that are encrypted with 3DES. It also uses RSA to encrypt resources.(Citation: Securelist WhiteBear Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--deb7df24-689e-4e4e-909f-a270241ab65a`.
