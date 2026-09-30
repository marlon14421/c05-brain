---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1568"
stix_relationship_id: "relationship--6a521aa4-d389-4ef4-bd24-442d8af23333"
---
# Relationship 5169: S0449 — uses → T1568

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Maze](https://attack.mitre.org/software/S0449) has forged POST strings with a random choice from a list of possibilities including "forum", "php", "view", etc. while making connection with the C2, hindering detection efforts.(Citation: McAfee Maze March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a521aa4-d389-4ef4-bd24-442d8af23333`.
