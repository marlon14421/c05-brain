---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1559.001"
stix_relationship_id: "relationship--2cae8d8d-e0de-4793-9acf-d21508189bf9"
---
# Relationship 3015: S0260 — uses → T1559.001

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) can use the ITaskService , ITaskDefinition and ITaskSettings COM interfaces to schedule a task.(Citation: ESET InvisiMole June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2cae8d8d-e0de-4793-9acf-d21508189bf9`.
