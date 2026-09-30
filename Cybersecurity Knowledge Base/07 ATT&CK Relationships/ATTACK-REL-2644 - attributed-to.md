---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0025"
target_object: "G0034"
stix_relationship_id: "relationship--90647f03-38a4-4364-a3af-53640a81360e"
---
# Relationship 2644: C0025 — attributed-to → G0034

**Source object:** [[01 ATT&CK/C0025 - 2016 Ukraine Electric Power Attack|C0025: 2016 Ukraine Electric Power Attack]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: US District Court Indictment GRU Unit 74455 October 2020)(Citation: Joe Slowik August 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90647f03-38a4-4364-a3af-53640a81360e`.
