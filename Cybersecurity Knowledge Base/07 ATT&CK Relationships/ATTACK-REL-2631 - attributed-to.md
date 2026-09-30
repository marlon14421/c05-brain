---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0011"
target_object: "G0134"
stix_relationship_id: "relationship--751e795e-7c1a-4ba1-bb20-636aed025df9"
---
# Relationship 2631: C0011 — attributed-to → G0134

**Source object:** [[01 ATT&CK/C0011 - C0011|C0011: C0011]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: Cisco Talos Transparent Tribe Education Campaign July 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--751e795e-7c1a-4ba1-bb20-636aed025df9`.
