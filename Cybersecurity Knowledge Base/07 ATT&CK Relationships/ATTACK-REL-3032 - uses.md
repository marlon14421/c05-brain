---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1497.001"
stix_relationship_id: "relationship--e289222f-0544-47cc-b0b6-72657d92d196"
---
# Relationship 3032: S1111 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) queries system resources on an infected machine to identify if it is executing in a sandbox or virtualized environment.(Citation: Ensilo Darkgate 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e289222f-0544-47cc-b0b6-72657d92d196`.
