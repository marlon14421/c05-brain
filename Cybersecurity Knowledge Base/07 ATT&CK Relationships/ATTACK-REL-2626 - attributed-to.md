---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0051"
target_object: "G0007"
stix_relationship_id: "relationship--f113a6b7-ffe0-4fe4-9c29-75936a093f7a"
---
# Relationship 2626: C0051 — attributed-to → G0007

**Source object:** [[01 ATT&CK/C0051 - APT28 Nearest Neighbor Campaign|C0051: APT28 Nearest Neighbor Campaign]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[APT28 Nearest Neighbor Campaign](https://attack.mitre.org/campaigns/C0051) was conducted by [APT28](https://attack.mitre.org/groups/G0007) from early February 2022 to November 2024.(Citation: Nearest Neighbor Volexity)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f113a6b7-ffe0-4fe4-9c29-75936a093f7a`.
