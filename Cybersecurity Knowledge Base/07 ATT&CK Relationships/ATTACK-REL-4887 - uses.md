---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1026"
target_object: "T1120"
stix_relationship_id: "relationship--3146b7d3-26c9-47c4-b114-d39a4a786fc9"
---
# Relationship 4887: S1026 — uses → T1120

**Source object:** [[01 ATT&CK/S1026 - Mongall|S1026: Mongall]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mongall](https://attack.mitre.org/software/S1026) can identify removable media attached to compromised hosts.(Citation: SentinelOne Aoqin Dragon June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3146b7d3-26c9-47c4-b114-d39a4a786fc9`.
