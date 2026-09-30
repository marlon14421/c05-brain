---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1056.004"
stix_relationship_id: "relationship--01e4bf9a-3d9c-4381-aa9c-cca73376c771"
---
# Relationship 6844: S0330 — uses → T1056.004

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.004 - Credential API Hooking|T1056.004: Credential API Hooking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) hooks processes by leveraging its own IAT hooked functions.(Citation: GDATA Zeus Panda June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01e4bf9a-3d9c-4381-aa9c-cca73376c771`.
