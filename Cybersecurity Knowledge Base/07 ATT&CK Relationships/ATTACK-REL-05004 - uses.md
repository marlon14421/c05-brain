---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0004"
target_object: "T1046"
stix_relationship_id: "relationship--069bd80b-9f39-46c6-a9dc-b61e42a2f91e"
---
# Relationship 5004: C0004 — uses → T1046

**Source object:** [[01 ATT&CK/C0004 - CostaRicto|C0004: CostaRicto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [CostaRicto](https://attack.mitre.org/campaigns/C0004), the threat actors employed nmap and pscan to scan target environments.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--069bd80b-9f39-46c6-a9dc-b61e42a2f91e`.
