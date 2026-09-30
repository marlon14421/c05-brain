---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1005"
target_object: "T1583.006"
stix_relationship_id: "relationship--ba747d29-53c9-4841-bbbe-93527c789e63"
---
# Relationship 2769: G1005 — uses → T1583.006

**Source object:** [[01 ATT&CK/G1005 - POLONIUM|G1005: POLONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POLONIUM](https://attack.mitre.org/groups/G1005) has created and used legitimate Microsoft OneDrive accounts for their operations.(Citation: Microsoft POLONIUM June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba747d29-53c9-4841-bbbe-93527c789e63`.
