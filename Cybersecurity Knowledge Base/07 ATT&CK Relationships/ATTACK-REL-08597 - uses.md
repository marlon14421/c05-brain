---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0355"
target_object: "T1547.001"
stix_relationship_id: "relationship--11471266-5136-4cd8-a1ef-d847f33ab6de"
---
# Relationship 8597: S0355 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0355 - Final1stspy|S0355: Final1stspy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Final1stspy](https://attack.mitre.org/software/S0355) creates a Registry Run key to establish persistence.(Citation: Unit 42 Nokki Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11471266-5136-4cd8-a1ef-d847f33ab6de`.
