---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1565"
stix_relationship_id: "relationship--3a75d307-2fde-412e-b01e-8cb0e157e762"
---
# Relationship 6240: G1016 — uses → T1565

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1565 - Data Manipulation|T1565: Data Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has injected fraudulent transactions into compromised networks that mimic legitimate behavior to siphon off incremental amounts of money.(Citation: Sygnia Elephant Beetle Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a75d307-2fde-412e-b01e-8cb0e157e762`.
