---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1013"
target_object: "T1053.005"
stix_relationship_id: "relationship--5859c58f-fc6a-4a08-ac8b-96fd21175814"
---
# Relationship 3611: S1013 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1013 - ZxxZ|S1013: ZxxZ]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZxxZ](https://attack.mitre.org/software/S1013) has used scheduled tasks for persistence and execution.(Citation: Cisco Talos Bitter Bangladesh May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5859c58f-fc6a-4a08-ac8b-96fd21175814`.
