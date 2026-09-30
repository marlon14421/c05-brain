---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1147"
target_object: "T1033"
stix_relationship_id: "relationship--ddd70255-e5c4-4812-93e5-a20cdf993330"
---
# Relationship 4606: S1147 — uses → T1033

**Source object:** [[01 ATT&CK/S1147 - Nightdoor|S1147: Nightdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) gathers information on victim system users and usernames.(Citation: ESET EvasivePanda 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ddd70255-e5c4-4812-93e5-a20cdf993330`.
