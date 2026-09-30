---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0027"
target_object: "G1015"
stix_relationship_id: "relationship--e662ff77-e38c-4a8b-ac49-cfb98ad01b47"
---
# Relationship 2646: C0027 — attributed-to → G1015

**Source object:** [[01 ATT&CK/C0027 - C0027|C0027: C0027]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: Crowdstrike TELCO BPO Campaign December 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e662ff77-e38c-4a8b-ac49-cfb98ad01b47`.
