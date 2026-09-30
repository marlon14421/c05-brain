---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1204.001"
stix_relationship_id: "relationship--393317c3-7dd7-487c-a2cb-81dfe4333ea3"
---
# Relationship 3155: S0198 — uses → T1204.001

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) has been executed through convincing victims into clicking malicious links.(Citation: FireEye NETWIRE March 2019)(Citation: Unit 42 NETWIRE April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--393317c3-7dd7-487c-a2cb-81dfe4333ea3`.
