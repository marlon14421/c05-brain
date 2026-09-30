---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1027.010"
stix_relationship_id: "relationship--e17c193a-d616-42d3-9525-940f3424c96c"
---
# Relationship 7653: G0047 — uses → T1027.010

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has used obfuscated or encrypted scripts.(Citation: ESET Gamaredon June 2020)(Citation: Microsoft Actinium February 2022)(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)(Citation: ESET Gamaredon Sept2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e17c193a-d616-42d3-9525-940f3424c96c`.
