---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0033"
target_object: "G0056"
stix_relationship_id: "relationship--f372697e-b661-4995-9920-4ec0a9060ebb"
---
# Relationship 2640: C0033 — attributed-to → G0056

**Source object:** [[01 ATT&CK/C0033 - C0033|C0033: C0033]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0056 - PROMETHIUM|G0056: PROMETHIUM]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: Talos Promethium June 2020)(Citation: Bitdefender StrongPity June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f372697e-b661-4995-9920-4ec0a9060ebb`.
