---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0041"
target_object: "S0125"
stix_relationship_id: "relationship--edea5971-fc27-4637-8de9-aabcd50784a7"
---
# Relationship 9856: G0041 — uses → S0125

**Source object:** [[01 ATT&CK/G0041 - Strider|G0041: Strider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Strider Blog)(Citation: Kaspersky ProjectSauron Blog)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edea5971-fc27-4637-8de9-aabcd50784a7`.
