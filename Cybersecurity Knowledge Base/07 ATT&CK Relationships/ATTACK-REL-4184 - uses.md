---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1088"
target_object: "T1053.005"
stix_relationship_id: "relationship--d61205cb-8b80-49c1-ac2c-76b0770d3e40"
---
# Relationship 4184: S1088 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1088 - Disco|S1088: Disco]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Disco](https://attack.mitre.org/software/S1088) can create a scheduled task to run every minute for persistence.(Citation: MoustachedBouncer ESET August 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d61205cb-8b80-49c1-ac2c-76b0770d3e40`.
