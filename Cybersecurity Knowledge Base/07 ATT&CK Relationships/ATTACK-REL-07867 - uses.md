---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0090"
target_object: "T1112"
stix_relationship_id: "relationship--bad90106-a150-4d76-b39f-f35aab4ac766"
---
# Relationship 7867: S0090 — uses → T1112

**Source object:** [[01 ATT&CK/S0090 - Rover|S0090: Rover]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rover](https://attack.mitre.org/software/S0090) has functionality to remove Registry Run key persistence as a cleanup procedure.(Citation: Palo Alto Rover)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bad90106-a150-4d76-b39f-f35aab4ac766`.
