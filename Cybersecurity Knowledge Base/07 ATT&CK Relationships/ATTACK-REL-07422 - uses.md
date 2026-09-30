---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0613"
target_object: "T1027.013"
stix_relationship_id: "relationship--798a3e14-1c98-4bac-af2d-137367f78912"
---
# Relationship 7422: S0613 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0613 - PS1|S0613: PS1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PS1](https://attack.mitre.org/software/S0613) is distributed as a set of encrypted files and scripts.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--798a3e14-1c98-4bac-af2d-137367f78912`.
