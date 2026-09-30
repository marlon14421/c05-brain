---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0064"
target_object: "T1566.002"
stix_relationship_id: "relationship--639e7b8d-57d7-4c1d-8f42-1496606ea666"
---
# Relationship 4207: G0064 — uses → T1566.002

**Source object:** [[01 ATT&CK/G0064 - APT33|G0064: APT33]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT33](https://attack.mitre.org/groups/G0064) has sent spearphishing emails containing links to .hta files.(Citation: FireEye APT33 Sept 2017)(Citation: Symantec Elfin Mar 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--639e7b8d-57d7-4c1d-8f42-1496606ea666`.
