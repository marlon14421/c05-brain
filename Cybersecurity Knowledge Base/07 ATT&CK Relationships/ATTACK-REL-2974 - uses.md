---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0380"
target_object: "T1012"
stix_relationship_id: "relationship--b7316e86-545b-4397-9b1f-d05a8ea64f4f"
---
# Relationship 2974: S0380 — uses → T1012

**Source object:** [[01 ATT&CK/S0380 - StoneDrill|S0380: StoneDrill]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StoneDrill](https://attack.mitre.org/software/S0380) has looked in the registry to find the default browser path.(Citation: Kaspersky StoneDrill 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7316e86-545b-4397-9b1f-d05a8ea64f4f`.
