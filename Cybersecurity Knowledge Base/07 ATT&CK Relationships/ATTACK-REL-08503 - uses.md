---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0161"
target_object: "T1033"
stix_relationship_id: "relationship--31cd4eb1-f7b3-4030-b087-388d55faba03"
---
# Relationship 8503: S0161 — uses → T1033

**Source object:** [[01 ATT&CK/S0161 - XAgentOSX|S0161: XAgentOSX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XAgentOSX](https://attack.mitre.org/software/S0161) contains the getInfoOSX function to return the OS X version as well as the current user.(Citation: XAgentOSX 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31cd4eb1-f7b3-4030-b087-388d55faba03`.
