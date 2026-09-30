---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0042"
target_object: "G0049"
stix_relationship_id: "relationship--2f87d195-6eb2-49d2-8dcf-a7bd4163cd09"
---
# Relationship 2630: C0042 — attributed-to → G0049

**Source object:** [[01 ATT&CK/C0042 - Outer Space|C0042: Outer Space]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ESET OilRig Campaigns Sep 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f87d195-6eb2-49d2-8dcf-a7bd4163cd09`.
