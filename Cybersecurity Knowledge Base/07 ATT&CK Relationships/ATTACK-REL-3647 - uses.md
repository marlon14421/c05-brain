---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1028"
target_object: "T1005"
stix_relationship_id: "relationship--fa0bc7fd-2e00-435b-8cb3-0ade491d1259"
---
# Relationship 3647: S1028 — uses → T1005

**Source object:** [[01 ATT&CK/S1028 - Action RAT|S1028: Action RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Action RAT](https://attack.mitre.org/software/S1028) can collect local data from an infected machine.(Citation: MalwareBytes SideCopy Dec 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa0bc7fd-2e00-435b-8cb3-0ade491d1259`.
