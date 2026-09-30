---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1224"
target_object: "T1205.002"
stix_relationship_id: "relationship--1631ddf9-4cce-458f-870d-94dd2e83dbf2"
---
# Relationship 2950: S1224 — uses → T1205.002

**Source object:** [[01 ATT&CK/S1224 - CASTLETAP|S1224: CASTLETAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205.002 - Socket Filters|T1205.002: Socket Filters]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CASTLETAP](https://attack.mitre.org/software/S1224) can listen for a specialized ICMP packet for activation on compromised network devices.(Citation: Mandiant Fortinet Zero Day)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1631ddf9-4cce-458f-870d-94dd2e83dbf2`.
