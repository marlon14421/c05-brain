---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0238"
target_object: "T1569.002"
stix_relationship_id: "relationship--5d6984fc-52cb-429b-9e68-64e656d9ad30"
---
# Relationship 7296: S0238 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0238 - Proxysvc|S0238: Proxysvc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Proxysvc](https://attack.mitre.org/software/S0238) registers itself as a service on the victim’s machine to run as a standalone process.(Citation: McAfee GhostSecret)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d6984fc-52cb-429b-9e68-64e656d9ad30`.
