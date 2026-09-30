---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1485"
stix_relationship_id: "relationship--d5166d3e-246b-473c-9ff0-c5cc97dd91de"
---
# Relationship 9435: S0089 — uses → T1485

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackEnergy](https://attack.mitre.org/software/S0089) 2 contains a "Destroy" plug-in that destroys data stored on victim hard drives by overwriting file contents.(Citation: Securelist BlackEnergy Feb 2015)(Citation: ESET BlackEnergy Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5166d3e-246b-473c-9ff0-c5cc97dd91de`.
