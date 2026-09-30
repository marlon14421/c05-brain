---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0124"
target_object: "T1547.001"
stix_relationship_id: "relationship--02a629d3-b970-43e8-a11b-79f35107a4c0"
---
# Relationship 6089: S0124 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pisloader](https://attack.mitre.org/software/S0124) establishes persistence via a Registry Run key.(Citation: Palo Alto DNS Requests)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02a629d3-b970-43e8-a11b-79f35107a4c0`.
