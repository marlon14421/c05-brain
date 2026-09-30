---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "T1036.005"
stix_relationship_id: "relationship--7148e604-1e3a-4a37-be3e-cde2fe20f9b6"
---
# Relationship 4177: G0019 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Naikon](https://attack.mitre.org/groups/G0019) has disguised malicious programs as Google Chrome, Adobe, and VMware executables.(Citation: Bitdefender Naikon April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7148e604-1e3a-4a37-be3e-cde2fe20f9b6`.
