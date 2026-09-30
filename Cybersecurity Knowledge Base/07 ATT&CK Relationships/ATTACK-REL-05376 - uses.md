---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0254"
target_object: "T1057"
stix_relationship_id: "relationship--91b6a6e1-c0eb-4bd8-84d4-4c31caf2ba6a"
---
# Relationship 5376: S0254 — uses → T1057

**Source object:** [[01 ATT&CK/S0254 - PLAINTEE|S0254: PLAINTEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PLAINTEE](https://attack.mitre.org/software/S0254) performs the tasklist command to list running processes.(Citation: Rancor Unit42 June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91b6a6e1-c0eb-4bd8-84d4-4c31caf2ba6a`.
