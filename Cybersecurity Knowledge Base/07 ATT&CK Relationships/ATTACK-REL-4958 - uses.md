---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0021"
target_object: "S0547"
stix_relationship_id: "relationship--41b74267-f604-4581-b1ca-4f1907a82245"
---
# Relationship 4958: G0021 — uses → S0547

**Source object:** [[01 ATT&CK/G0021 - Molerats|G0021: Molerats]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0547 - DropBook|S0547: DropBook]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cybereason Molerats Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41b74267-f604-4581-b1ca-4f1907a82245`.
