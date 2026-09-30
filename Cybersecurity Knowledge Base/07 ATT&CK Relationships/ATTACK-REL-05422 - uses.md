---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0554"
target_object: "T1039"
stix_relationship_id: "relationship--59c58c73-046c-4e01-9ced-8c049381fcd2"
---
# Relationship 5422: S0554 — uses → T1039

**Source object:** [[01 ATT&CK/S0554 - Egregor|S0554: Egregor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1039 - Data from Network Shared Drive|T1039: Data from Network Shared Drive]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Egregor](https://attack.mitre.org/software/S0554) can collect any files found in the enumerated drivers before sending it to its C2 channel.(Citation: NHS Digital Egregor Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59c58c73-046c-4e01-9ced-8c049381fcd2`.
