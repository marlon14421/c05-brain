---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0087"
target_object: "T1573.001"
stix_relationship_id: "relationship--34e9fc0a-75b9-4100-91ef-30ca3225958a"
---
# Relationship 7760: S0087 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0087 - Hi-Zor|S0087: Hi-Zor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hi-Zor](https://attack.mitre.org/software/S0087) encrypts C2 traffic with a double XOR using two distinct single-byte keys.(Citation: Fidelis Hi-Zor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34e9fc0a-75b9-4100-91ef-30ca3225958a`.
