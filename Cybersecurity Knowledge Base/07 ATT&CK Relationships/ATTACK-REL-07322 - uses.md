---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0079"
target_object: "S0002"
stix_relationship_id: "relationship--17aef45b-9a3c-4192-af31-4a21300a90e0"
---
# Relationship 7322: G0079 — uses → S0002

**Source object:** [[01 ATT&CK/G0079 - DarkHydrus|G0079: DarkHydrus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Unit 42 DarkHydrus July 2018)(Citation: Unit 42 Playbook Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17aef45b-9a3c-4192-af31-4a21300a90e0`.
