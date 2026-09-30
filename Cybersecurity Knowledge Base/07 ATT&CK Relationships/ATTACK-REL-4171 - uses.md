---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1235"
target_object: "T1543.003"
stix_relationship_id: "relationship--5eec8391-e708-4a90-86c0-259fff53af8d"
---
# Relationship 4171: S1235 — uses → T1543.003

**Source object:** [[01 ATT&CK/S1235 - CorKLOG|S1235: CorKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CorKLOG](https://attack.mitre.org/software/S1235) has created a service to establish persistence.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5eec8391-e708-4a90-86c0-259fff53af8d`.
