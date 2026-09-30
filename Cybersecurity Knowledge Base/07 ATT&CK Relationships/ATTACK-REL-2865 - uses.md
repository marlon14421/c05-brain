---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0065"
target_object: "T1584.004"
stix_relationship_id: "relationship--8191e3f4-df01-42c0-925b-0038772afb17"
---
# Relationship 2865: G0065 — uses → T1584.004

**Source object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) has used compromised legitimate websites as command and control nodes for operations.(Citation: CISA Leviathan 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8191e3f4-df01-42c0-925b-0038772afb17`.
