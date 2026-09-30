---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0554"
target_object: "T1574.001"
stix_relationship_id: "relationship--9eaf89d5-01aa-4758-a2a9-abac83d2a17e"
---
# Relationship 9584: S0554 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0554 - Egregor|S0554: Egregor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Egregor](https://attack.mitre.org/software/S0554) has used DLL side-loading to execute its payload.(Citation: Cyble Egregor Oct 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9eaf89d5-01aa-4758-a2a9-abac83d2a17e`.
