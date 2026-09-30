---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0244"
target_object: "T1027.001"
stix_relationship_id: "relationship--e4e36dcb-9c07-4c22-a182-61ac194a434f"
---
# Relationship 8927: S0244 — uses → T1027.001

**Source object:** [[01 ATT&CK/S0244 - Comnie|S0244: Comnie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.001 - Binary Padding|T1027.001: Binary Padding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Comnie](https://attack.mitre.org/software/S0244) appends a total of 64MB of garbage data to a file to deter any security products in place that may be scanning files on disk.(Citation: Palo Alto Comnie)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4e36dcb-9c07-4c22-a182-61ac194a434f`.
