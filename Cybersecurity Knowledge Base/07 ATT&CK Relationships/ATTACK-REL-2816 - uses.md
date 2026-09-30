---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1669"
stix_relationship_id: "relationship--3bb368c6-fcb8-40f8-85bc-1a0124dd5926"
---
# Relationship 2816: G0007 — uses → T1669

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1669 - Wi-Fi Networks|T1669: Wi-Fi Networks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has exploited open Wi-Fi access points for initial access to target devices using the network.(Citation: Nearest Neighbor Volexity)(Citation: DOJ GRU Charges 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3bb368c6-fcb8-40f8-85bc-1a0124dd5926`.
