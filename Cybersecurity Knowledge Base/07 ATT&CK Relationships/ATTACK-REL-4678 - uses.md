---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1585.001"
stix_relationship_id: "relationship--e562688d-a5e3-4a17-95dd-8ef7488e015e"
---
# Relationship 4678: G0059 — uses → T1585.001

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.001 - Social Media Accounts|T1585.001: Social Media Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has created fake LinkedIn and other social media accounts to contact targets and convince them--through messages and voice communications--to open malicious links.(Citation: ClearSky Kittens Back 3 August 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e562688d-a5e3-4a17-95dd-8ef7488e015e`.
