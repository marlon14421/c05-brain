---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0057"
target_object: "G1049"
stix_relationship_id: "relationship--7c78e819-d227-4469-967d-08dc9f50edc9"
---
# Relationship 2621: C0057 — attributed-to → G1049

**Source object:** [[01 ATT&CK/C0057 - 3CX Supply Chain Attack|C0057: 3CX Supply Chain Attack]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1049 - AppleJeus|G1049: AppleJeus]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: Mandiant 3cx UNC4736 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c78e819-d227-4469-967d-08dc9f50edc9`.
