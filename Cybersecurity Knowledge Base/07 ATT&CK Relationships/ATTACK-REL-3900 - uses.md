---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0265"
target_object: "T1069.001"
stix_relationship_id: "relationship--77bd9ea1-9401-4128-a78a-bd28d43a6c99"
---
# Relationship 3900: S0265 — uses → T1069.001

**Source object:** [[01 ATT&CK/S0265 - Kazuar|S0265: Kazuar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kazuar](https://attack.mitre.org/software/S0265) gathers information about local groups and members.(Citation: Unit 42 Kazuar May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77bd9ea1-9401-4128-a78a-bd28d43a6c99`.
