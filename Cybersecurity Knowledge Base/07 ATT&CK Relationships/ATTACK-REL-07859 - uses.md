---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0657"
target_object: "T1016"
stix_relationship_id: "relationship--07720e8d-fd8a-449c-ac32-484ccf989694"
---
# Relationship 7859: S0657 — uses → T1016

**Source object:** [[01 ATT&CK/S0657 - BLUELIGHT|S0657: BLUELIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLUELIGHT](https://attack.mitre.org/software/S0657) can collect IP information from the victim’s machine.(Citation: Volexity InkySquid BLUELIGHT August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07720e8d-fd8a-449c-ac32-484ccf989694`.
