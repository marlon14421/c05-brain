---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "S0075"
stix_relationship_id: "relationship--e54b8ce9-1ebf-4ab0-a7d2-704219ffccab"
---
# Relationship 3488: G1017 — uses → S0075

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0075 - Reg|S0075: Reg]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: CISA AA24-038A PRC Critical Infrastructure February 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e54b8ce9-1ebf-4ab0-a7d2-704219ffccab`.
