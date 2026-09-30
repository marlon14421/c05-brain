---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0022"
target_object: "G0032"
stix_relationship_id: "relationship--4b66e057-adbc-498d-99ee-156e0d17bd53"
---
# Relationship 2622: C0022 — attributed-to → G0032

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ClearSky Lazarus Aug 2020)(Citation: McAfee Lazarus Jul 2020)(Citation: McAfee Lazarus Nov 2020)(Citation: ESET Lazarus Jun 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b66e057-adbc-498d-99ee-156e0d17bd53`.
