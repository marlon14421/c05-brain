---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0187"
target_object: "T1036.005"
stix_relationship_id: "relationship--d297b77f-9511-429a-b148-d7b8f0b5b502"
---
# Relationship 6817: S0187 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0187 - Daserf|S0187: Daserf]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Daserf](https://attack.mitre.org/software/S0187) uses file and folder names related to legitimate programs in order to blend in, such as HP, Intel, Adobe, and perflogs.(Citation: Symantec Tick Apr 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d297b77f-9511-429a-b148-d7b8f0b5b502`.
