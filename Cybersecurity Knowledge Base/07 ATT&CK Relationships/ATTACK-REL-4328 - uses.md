---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1038"
target_object: "S1160"
stix_relationship_id: "relationship--a3f0a84b-e32a-46d3-8ada-189f2d8796c8"
---
# Relationship 4328: G1038 — uses → S1160

**Source object:** [[01 ATT&CK/G1038 - TA578|G1038: TA578]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Latrodectus APR 2024)(Citation: Bitsight Latrodectus June 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3f0a84b-e32a-46d3-8ada-189f2d8796c8`.
