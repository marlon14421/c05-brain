---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1590.004"
stix_relationship_id: "relationship--b79256c4-9067-44ed-8e96-8b11a4c348e8"
---
# Relationship 3871: G1016 — uses → T1590.004

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1590.004 - Network Topology|T1590.004: Network Topology]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has searched for infrastructure that can provide remote access to an environment for targeting efforts.(Citation: Mandiant FIN13 Aug 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b79256c4-9067-44ed-8e96-8b11a4c348e8`.
