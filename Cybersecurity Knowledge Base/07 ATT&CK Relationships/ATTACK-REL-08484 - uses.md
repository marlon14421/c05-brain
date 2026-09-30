---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1022"
target_object: "S0154"
stix_relationship_id: "relationship--56f08580-ffab-4c02-8702-adbe4de12a6a"
---
# Relationship 8484: G1022 — uses → S0154

**Source object:** [[01 ATT&CK/G1022 - ToddyCat|G1022: ToddyCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56f08580-ffab-4c02-8702-adbe4de12a6a`.
