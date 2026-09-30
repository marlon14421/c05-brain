---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0353"
target_object: "T1016"
stix_relationship_id: "relationship--e3347969-1cfd-43f3-b871-65874c4b2f95"
---
# Relationship 5483: S0353 — uses → T1016

**Source object:** [[01 ATT&CK/S0353 - NOKKI|S0353: NOKKI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOKKI](https://attack.mitre.org/software/S0353) can gather information on the victim IP address.(Citation: Unit 42 NOKKI Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3347969-1cfd-43f3-b871-65874c4b2f95`.
