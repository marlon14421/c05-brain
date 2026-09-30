---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0021"
target_object: "S0546"
stix_relationship_id: "relationship--8f321c37-1463-4b55-a3d5-f2e517ede0b7"
---
# Relationship 4748: G0021 — uses → S0546

**Source object:** [[01 ATT&CK/G0021 - Molerats|G0021: Molerats]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cybereason Molerats Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f321c37-1463-4b55-a3d5-f2e517ede0b7`.
