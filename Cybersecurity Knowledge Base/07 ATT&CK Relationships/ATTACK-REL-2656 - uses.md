---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1018"
stix_relationship_id: "relationship--bae9c6ec-2d33-418b-b7db-8b99af22e32f"
---
# Relationship 2656: G1057 — uses → T1018

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has enumerated the internal subnet using ` cat /etc/hosts | grep -E "[redacted_victim_string]"`.(Citation: Google_SHOracle_Jun2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bae9c6ec-2d33-418b-b7db-8b99af22e32f`.
