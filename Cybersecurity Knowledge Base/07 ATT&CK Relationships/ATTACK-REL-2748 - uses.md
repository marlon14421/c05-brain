---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "T1033"
stix_relationship_id: "relationship--d1d496f1-fa91-404e-a93a-97670817717a"
---
# Relationship 2748: G0069 — uses → T1033

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) has used malware that can collect the victim’s username.(Citation: Securelist MuddyWater Oct 2018)(Citation: Trend Micro Muddy Water March 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1d496f1-fa91-404e-a93a-97670817717a`.
