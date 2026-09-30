---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0150"
target_object: "T1546.003"
stix_relationship_id: "relationship--f758836e-91b2-4651-ba72-d827553b668c"
---
# Relationship 4451: S0150 — uses → T1546.003

**Source object:** [[01 ATT&CK/S0150 - POSHSPY|S0150: POSHSPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.003 - Windows Management Instrumentation Event Subscription|T1546.003: Windows Management Instrumentation Event Subscription]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POSHSPY](https://attack.mitre.org/software/S0150) uses a WMI event subscription to establish persistence.(Citation: FireEye POSHSPY April 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f758836e-91b2-4651-ba72-d827553b668c`.
