---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "T1078"
stix_relationship_id: "relationship--c4b47c6e-2a98-4b46-a0dc-39d40361e3f7"
---
# Relationship 4160: G1043 — uses → T1078

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) has gained access to victim environments through legitimate VPN credentials.(Citation: Cisco BlackByte 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4b47c6e-2a98-4b46-a0dc-39d40361e3f7`.
