---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1027.013"
stix_relationship_id: "relationship--5f3cac8e-55b8-4fb9-b0dd-e83939aa81ad"
---
# Relationship 6073: G0099 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has used encoded and obfuscated files, images, and executables.(Citation: Kaspersky BlindEagle AUG 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f3cac8e-55b8-4fb9-b0dd-e83939aa81ad`.
