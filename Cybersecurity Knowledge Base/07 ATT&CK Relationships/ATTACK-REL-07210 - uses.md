---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "S0363"
stix_relationship_id: "relationship--464c9ae2-09b1-499d-8477-c05926537e6b"
---
# Relationship 7210: G0090 — uses → S0363

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Lab52 WIRTE Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--464c9ae2-09b1-499d-8477-c05926537e6b`.
