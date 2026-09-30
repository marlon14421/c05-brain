---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1138"
target_object: "T1614.001"
stix_relationship_id: "relationship--5c12d816-bb1e-4f3b-8247-7a1780d2db01"
---
# Relationship 3741: S1138 — uses → T1614.001

**Source object:** [[01 ATT&CK/S1138 - Gootloader|S1138: Gootloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gootloader](https://attack.mitre.org/software/S1138) can determine if a victim's computer is running an operating system with specific language preferences.(Citation: Sophos Gootloader)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c12d816-bb1e-4f3b-8247-7a1780d2db01`.
