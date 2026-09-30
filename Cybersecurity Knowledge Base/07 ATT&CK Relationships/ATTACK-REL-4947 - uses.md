---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1036"
target_object: "T1585.001"
stix_relationship_id: "relationship--f4980470-c6f6-4032-8d99-e707861a4180"
---
# Relationship 4947: G1036 — uses → T1585.001

**Source object:** [[01 ATT&CK/G1036 - Moonstone Sleet|G1036: Moonstone Sleet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.001 - Social Media Accounts|T1585.001: Social Media Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Moonstone Sleet](https://attack.mitre.org/groups/G1036) has created social media accounts to interact with victims.(Citation: Microsoft Moonstone Sleet 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4980470-c6f6-4032-8d99-e707861a4180`.
