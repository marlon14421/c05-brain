---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0378"
target_object: "T1569.002"
stix_relationship_id: "relationship--37b7ba1e-5093-4a0d-920b-c86d3c9c766b"
---
# Relationship 9144: S0378 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0378 - PoshC2|S0378: PoshC2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoshC2](https://attack.mitre.org/software/S0378) contains an implementation of [PsExec](https://attack.mitre.org/software/S0029) for remote execution.(Citation: GitHub PoshC2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37b7ba1e-5093-4a0d-920b-c86d3c9c766b`.
