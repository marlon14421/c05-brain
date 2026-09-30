---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0349"
target_object: "T1003.001"
stix_relationship_id: "relationship--43619944-94e9-43d9-a761-8e4db2113eef"
---
# Relationship 4293: S0349 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LaZagne](https://attack.mitre.org/software/S0349) can perform credential dumping from memory to obtain account and password information.(Citation: GitHub LaZagne Dec 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43619944-94e9-43d9-a761-8e4db2113eef`.
