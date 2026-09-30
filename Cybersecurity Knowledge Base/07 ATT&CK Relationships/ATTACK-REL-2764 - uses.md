---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1505.003"
stix_relationship_id: "relationship--e2e3eae7-879c-456c-a216-be6be395a582"
---
# Relationship 2764: G1041 — uses → T1505.003

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) deployed the [SnappyTCP](https://attack.mitre.org/software/S1163) web shell during intrusion operations.(Citation: PWC Sea Turtle 2023)(Citation: Hunt Sea Turtle 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2e3eae7-879c-456c-a216-be6be395a582`.
