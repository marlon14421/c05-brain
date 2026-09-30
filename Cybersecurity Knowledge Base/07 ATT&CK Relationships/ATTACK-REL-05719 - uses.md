---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1204"
target_object: "T1016"
stix_relationship_id: "relationship--870d1e0e-6fde-41ab-aac0-72fd114f3377"
---
# Relationship 5719: S1204 — uses → T1016

**Source object:** [[01 ATT&CK/S1204 - cd00r|S1204: cd00r]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[cd00r](https://attack.mitre.org/software/S1204) can discover the IP for the network interface on the compromised device.(Citation: Hartrell cd00r 2002)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--870d1e0e-6fde-41ab-aac0-72fd114f3377`.
