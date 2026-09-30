---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0093"
target_object: "T1082"
stix_relationship_id: "relationship--f19234f6-5b59-4229-aae1-70df380a076a"
---
# Relationship 9165: S0093 — uses → T1082

**Source object:** [[01 ATT&CK/S0093 - Backdoor.Oldrea|S0093: Backdoor.Oldrea]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Backdoor.Oldrea](https://attack.mitre.org/software/S0093) collects information about the OS and computer name.(Citation: Symantec Dragonfly)(Citation: Gigamon Berserk Bear October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f19234f6-5b59-4229-aae1-70df380a076a`.
