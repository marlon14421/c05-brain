---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "S1086"
stix_relationship_id: "relationship--044e6bdf-a7d1-4f70-8591-193ad4fab387"
---
# Relationship 2726: G1018 — uses → S1086

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Proofpoint TA2541 February 2022)(Citation: Morphisec Snip3 May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--044e6bdf-a7d1-4f70-8591-193ad4fab387`.
