---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0269"
target_object: "T1016"
stix_relationship_id: "relationship--6c130246-6222-4395-8edc-cb325b437696"
---
# Relationship 4969: S0269 — uses → T1016

**Source object:** [[01 ATT&CK/S0269 - QUADAGENT|S0269: QUADAGENT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QUADAGENT](https://attack.mitre.org/software/S0269) gathers the current domain the victim system belongs to.(Citation: Unit 42 QUADAGENT July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c130246-6222-4395-8edc-cb325b437696`.
