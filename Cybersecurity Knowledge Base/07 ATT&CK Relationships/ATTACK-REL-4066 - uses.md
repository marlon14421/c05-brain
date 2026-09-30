---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1024"
target_object: "S0349"
stix_relationship_id: "relationship--e5328a4e-b37a-4020-b242-ea6c60605e02"
---
# Relationship 4066: G1024 — uses → S0349

**Source object:** [[01 ATT&CK/G1024 - Akira|G1024: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Arctic Wolf Akira 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e5328a4e-b37a-4020-b242-ea6c60605e02`.
