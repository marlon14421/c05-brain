---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1584.003"
stix_relationship_id: "relationship--b2f3bf33-8e22-4ab4-9358-3fda32cbea55"
---
# Relationship 3134: G1017 — uses → T1584.003

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.003 - Virtual Private Server|T1584.003: Virtual Private Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has compromised Virtual Private Servers (VPS) to proxy C2 traffic.(Citation: CISA AA24-038A PRC Critical Infrastructure February 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2f3bf33-8e22-4ab4-9358-3fda32cbea55`.
