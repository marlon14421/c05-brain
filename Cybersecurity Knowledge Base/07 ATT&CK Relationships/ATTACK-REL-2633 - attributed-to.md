---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0032"
target_object: "G0088"
stix_relationship_id: "relationship--dd10cc43-3f46-42f4-9230-69a0e2751ab2"
---
# Relationship 2633: C0032 — attributed-to → G0088

**Source object:** [[01 ATT&CK/C0032 - C0032|C0032: C0032]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0088 - TEMP.Veles|G0088: TEMP.Veles]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: FireEye TRITON 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd10cc43-3f46-42f4-9230-69a0e2751ab2`.
