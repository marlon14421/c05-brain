---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1112"
target_object: "T1132.001"
stix_relationship_id: "relationship--53ae8545-a24d-431c-a0ee-6d5b63278490"
---
# Relationship 5539: S1112 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1112 - STEADYPULSE|S1112: STEADYPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STEADYPULSE](https://attack.mitre.org/software/S1112) can transmit URL encoded data over C2.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53ae8545-a24d-431c-a0ee-6d5b63278490`.
