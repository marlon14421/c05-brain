---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0180"
target_object: "T1016"
stix_relationship_id: "relationship--9c4bbad5-4821-4059-b881-557c2a6db1a0"
---
# Relationship 7336: S0180 — uses → T1016

**Source object:** [[01 ATT&CK/S0180 - Volgmer|S0180: Volgmer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volgmer](https://attack.mitre.org/software/S0180) can gather the IP address from the victim's machine.(Citation: Symantec Volgmer Aug 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c4bbad5-4821-4059-b881-557c2a6db1a0`.
