---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1053.005"
stix_relationship_id: "relationship--cff83f53-0e10-4e98-9e2e-2a4b7d027d70"
---
# Relationship 4908: S0534 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bazar](https://attack.mitre.org/software/S0534) can create a scheduled task for persistence.(Citation: Cybereason Bazar July 2020)(Citation: NCC Group Team9 June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cff83f53-0e10-4e98-9e2e-2a4b7d027d70`.
