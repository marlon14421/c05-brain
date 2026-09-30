---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0441"
target_object: "T1547.001"
stix_relationship_id: "relationship--79bae99a-8480-4857-834b-fa823adca4c6"
---
# Relationship 7417: S0441 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0441 - PowerShower|S0441: PowerShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerShower](https://attack.mitre.org/software/S0441) sets up persistence with a Registry run key.(Citation: Unit 42 Inception November 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79bae99a-8480-4857-834b-fa823adca4c6`.
