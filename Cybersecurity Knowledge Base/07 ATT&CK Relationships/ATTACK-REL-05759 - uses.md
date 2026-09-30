---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "S0383"
stix_relationship_id: "relationship--60026624-0ae9-439a-8ee8-faee7ce6ddf0"
---
# Relationship 5759: G0092 — uses → S0383

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0383 - FlawedGrace|S0383: FlawedGrace]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Proofpoint TA505 Jan 2019)(Citation: Trend Micro TA505 June 2019)(Citation: Proofpoint TA505 October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60026624-0ae9-439a-8ee8-faee7ce6ddf0`.
