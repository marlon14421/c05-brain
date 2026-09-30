---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0068"
target_object: "S0202"
stix_relationship_id: "relationship--ebd51f84-cd09-4b40-88bd-bed2461996d7"
---
# Relationship 3363: G0068 — uses → S0202

**Source object:** [[01 ATT&CK/G0068 - PLATINUM|G0068: PLATINUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0202 - adbupd|S0202: adbupd]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Microsoft PLATINUM April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ebd51f84-cd09-4b40-88bd-bed2461996d7`.
