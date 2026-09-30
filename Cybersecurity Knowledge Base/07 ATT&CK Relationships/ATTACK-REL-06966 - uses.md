---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0470"
target_object: "T1106"
stix_relationship_id: "relationship--f8f24599-854a-4795-891b-c28d89b8ddcc"
---
# Relationship 6966: S0470 — uses → T1106

**Source object:** [[01 ATT&CK/S0470 - BBK|S0470: BBK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BBK](https://attack.mitre.org/software/S0470) has the ability to use the CreatePipe API to add a sub-process for execution via [cmd](https://attack.mitre.org/software/S0106).(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8f24599-854a-4795-891b-c28d89b8ddcc`.
