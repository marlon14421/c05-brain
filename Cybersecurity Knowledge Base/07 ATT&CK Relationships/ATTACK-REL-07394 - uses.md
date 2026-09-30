---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0340"
target_object: "T1041"
stix_relationship_id: "relationship--49267afd-b71b-4dd0-a68a-128e61f7bdfd"
---
# Relationship 7394: S0340 — uses → T1041

**Source object:** [[01 ATT&CK/S0340 - Octopus|S0340: Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Octopus](https://attack.mitre.org/software/S0340) has uploaded stolen files and data from a victim's machine over its C2 channel.(Citation: Securelist Octopus Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49267afd-b71b-4dd0-a68a-128e61f7bdfd`.
