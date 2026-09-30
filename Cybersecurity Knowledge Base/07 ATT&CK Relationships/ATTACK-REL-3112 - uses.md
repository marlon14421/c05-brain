---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0562"
target_object: "T1480.002"
stix_relationship_id: "relationship--9cb9a1a6-8fdf-4201-af7d-156a92d0f358"
---
# Relationship 3112: S0562 — uses → T1480.002

**Source object:** [[01 ATT&CK/S0562 - SUNSPOT|S0562: SUNSPOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNSPOT](https://attack.mitre.org/software/S0562) creates a mutex using the hard-coded value ` {12d61a41-4b74-7610-a4d8-3028d2f56395}` to ensure that only one instance of itself is running.(Citation: CrowdStrike SUNSPOT Implant January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cb9a1a6-8fdf-4201-af7d-156a92d0f358`.
