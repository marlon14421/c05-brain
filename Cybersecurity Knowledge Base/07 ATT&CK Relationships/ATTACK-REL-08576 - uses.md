---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1057"
stix_relationship_id: "relationship--c85af3d4-ab10-4c49-91c4-bff9054096b8"
---
# Relationship 8576: S0595 — uses → T1057

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) obtains a list of running processes using the function kill_unwanted .(Citation: wardle evilquest parti)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c85af3d4-ab10-4c49-91c4-bff9054096b8`.
