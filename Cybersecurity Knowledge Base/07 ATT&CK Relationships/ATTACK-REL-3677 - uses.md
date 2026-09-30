---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1038"
target_object: "S0483"
stix_relationship_id: "relationship--eeaeb818-cb48-4f67-9975-d783c52f3ca8"
---
# Relationship 3677: G1038 — uses → S0483

**Source object:** [[01 ATT&CK/G1038 - TA578|G1038: TA578]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Latrodectus APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eeaeb818-cb48-4f67-9975-d783c52f3ca8`.
