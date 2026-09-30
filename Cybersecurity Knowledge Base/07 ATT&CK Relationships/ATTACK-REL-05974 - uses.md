---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0244"
target_object: "T1547.001"
stix_relationship_id: "relationship--d490bb02-7dfc-4808-8109-29a3871f830a"
---
# Relationship 5974: S0244 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0244 - Comnie|S0244: Comnie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Comnie](https://attack.mitre.org/software/S0244) achieves persistence by adding a shortcut of itself to the startup path in the Registry.(Citation: Palo Alto Comnie)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d490bb02-7dfc-4808-8109-29a3871f830a`.
