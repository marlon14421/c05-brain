---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1055.012"
stix_relationship_id: "relationship--8b289eb7-6960-45c4-bea8-bbd9ace81055"
---
# Relationship 4488: G1018 — uses → T1055.012

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has used process hollowing to execute CyberGate malware.(Citation: Cisco Operation Layover September 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b289eb7-6960-45c4-bea8-bbd9ace81055`.
