---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0115"
target_object: "T1112"
stix_relationship_id: "relationship--924b50b9-7de3-4036-b732-c87d08971122"
---
# Relationship 3527: S0115 — uses → T1112

**Source object:** [[01 ATT&CK/S0115 - Crimson|S0115: Crimson]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Crimson](https://attack.mitre.org/software/S0115) can set a Registry key to determine how long it has been installed and possibly to indicate the version number.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--924b50b9-7de3-4036-b732-c87d08971122`.
