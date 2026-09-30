---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0042"
target_object: "T1217"
stix_relationship_id: "relationship--3c770dba-9357-4a2b-9431-37bf95c080c5"
---
# Relationship 4810: C0042 — uses → T1217

**Source object:** [[01 ATT&CK/C0042 - Outer Space|C0042: Outer Space]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Outer Space](https://attack.mitre.org/campaigns/C0042), [OilRig](https://attack.mitre.org/groups/G0049) used a Chrome data dumper named MKG.(Citation: ESET OilRig Campaigns Sep 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c770dba-9357-4a2b-9431-37bf95c080c5`.
