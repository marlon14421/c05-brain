---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "S0002"
stix_relationship_id: "relationship--ffa16031-220f-4bb3-9be4-241b4b43b53e"
---
# Relationship 2978: G1043 — uses → S0002

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) has used [Mimikatz](https://attack.mitre.org/software/S0002) for credential dumping during operations.(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffa16031-220f-4bb3-9be4-241b4b43b53e`.
