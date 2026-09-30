---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1036.005"
stix_relationship_id: "relationship--55eb87ba-64a9-4720-a3ce-fe03f66b074c"
---
# Relationship 6513: S1196 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) is typically installed via a dropper file that masquerades as a legitimate security program installation file.(Citation: S2W Troll Stealer 2024)(Citation: Symantec Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55eb87ba-64a9-4720-a3ce-fe03f66b074c`.
