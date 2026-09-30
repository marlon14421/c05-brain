---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1218.008"
stix_relationship_id: "relationship--1d10495f-64e6-43d9-85cd-4d74a8acdf7c"
---
# Relationship 3418: G0080 — uses → T1218.008

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.008 - Odbcconf|T1218.008: Odbcconf]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) has used odbcconf to proxy the execution of malicious DLL files.(Citation: TrendMicro Cobalt Group Nov 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d10495f-64e6-43d9-85cd-4d74a8acdf7c`.
