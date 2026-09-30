---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0663"
target_object: "T1106"
stix_relationship_id: "relationship--e28c174a-33d6-4fef-989f-7c58d0fb770d"
---
# Relationship 8867: S0663 — uses → T1106

**Source object:** [[01 ATT&CK/S0663 - SysUpdate|S0663: SysUpdate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SysUpdate](https://attack.mitre.org/software/S0663) can call the `GetNetworkParams` API as part of its C2 establishment process.(Citation: Lunghi Iron Tiger Linux)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e28c174a-33d6-4fef-989f-7c58d0fb770d`.
