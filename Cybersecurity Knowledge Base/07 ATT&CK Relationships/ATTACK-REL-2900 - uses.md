---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0226"
target_object: "T1053.005"
stix_relationship_id: "relationship--f3c37734-1f69-44ee-9e27-480ba68c79f4"
---
# Relationship 2900: S0226 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0226 - Smoke Loader|S0226: Smoke Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) launches a scheduled task.(Citation: Talos Smoke Loader July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3c37734-1f69-44ee-9e27-480ba68c79f4`.
