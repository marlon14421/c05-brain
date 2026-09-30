---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "S0552"
stix_relationship_id: "relationship--95cabb2e-3d68-40c9-8e84-14667ef9ef6a"
---
# Relationship 9601: G0129 — uses → S0552

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0552 - AdFind|S0552: AdFind]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has utilized [AdFind](https://attack.mitre.org/software/S0552) for enumerating domain groups, users, and computers.(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95cabb2e-3d68-40c9-8e84-14667ef9ef6a`.
