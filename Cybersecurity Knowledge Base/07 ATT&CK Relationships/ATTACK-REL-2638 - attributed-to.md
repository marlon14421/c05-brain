---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0044"
target_object: "G0049"
stix_relationship_id: "relationship--f0ce9b1b-9184-4071-9b02-1eb2f38f5856"
---
# Relationship 2638: C0044 — attributed-to → G0049

**Source object:** [[01 ATT&CK/C0044 - Juicy Mix|C0044: Juicy Mix]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ESET OilRig Campaigns Sep 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0ce9b1b-9184-4071-9b02-1eb2f38f5856`.
