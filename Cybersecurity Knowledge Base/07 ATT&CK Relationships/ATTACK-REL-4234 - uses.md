---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0572"
target_object: "T1069.001"
stix_relationship_id: "relationship--9c089e25-2028-4afb-9f05-b28d5055f444"
---
# Relationship 4234: S0572 — uses → T1069.001

**Source object:** [[01 ATT&CK/S0572 - Caterpillar WebShell|S0572: Caterpillar WebShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Caterpillar WebShell](https://attack.mitre.org/software/S0572) can obtain a list of local groups of users from a system.(Citation: ClearSky Lebanese Cedar Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c089e25-2028-4afb-9f05-b28d5055f444`.
