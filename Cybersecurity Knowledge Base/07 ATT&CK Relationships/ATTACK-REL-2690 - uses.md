---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0053"
target_object: "T1583.003"
stix_relationship_id: "relationship--1bb1fe87-de75-4030-9b9c-691671412be1"
---
# Relationship 2690: C0053 — uses → T1583.003

**Source object:** [[01 ATT&CK/C0053 - FLORAHOX Activity|C0053: FLORAHOX Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.003 - Virtual Private Server|T1583.003: Virtual Private Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) has used acquired Virtual Private Servers as control systems for the ORB network.(Citation: ORB Mandiant)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1bb1fe87-de75-4030-9b9c-691671412be1`.
