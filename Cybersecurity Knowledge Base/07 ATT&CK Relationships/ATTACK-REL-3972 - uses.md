---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1546.003"
stix_relationship_id: "relationship--46e81587-e960-4277-9c3b-af2bdc328176"
---
# Relationship 3972: S1059 — uses → T1546.003

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.003 - Windows Management Instrumentation Event Subscription|T1546.003: Windows Management Instrumentation Event Subscription]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) registered a WMI event subscription consumer called "hard_disk_stat" to establish persistence.(Citation: SentinelLabs Metador Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--46e81587-e960-4277-9c3b-af2bdc328176`.
