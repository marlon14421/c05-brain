---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0039"
target_object: "S1154"
stix_relationship_id: "relationship--3d241ebf-728b-4aea-99a5-404a28d708d5"
---
# Relationship 3146: C0039 — uses → S1154

**Source object:** [[01 ATT&CK/C0039 - Versa Director Zero Day Exploitation|C0039: Versa Director Zero Day Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1154 - VersaMem|S1154: VersaMem]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VersaMem](https://attack.mitre.org/software/S1154) was used during [Versa Director Zero Day Exploitation](https://attack.mitre.org/campaigns/C0039) by [Volt Typhoon](https://attack.mitre.org/groups/G1017).(Citation: Lumen Versa 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d241ebf-728b-4aea-99a5-404a28d708d5`.
