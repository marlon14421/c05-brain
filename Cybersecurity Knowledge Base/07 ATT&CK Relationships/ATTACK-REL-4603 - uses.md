---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1053.005"
stix_relationship_id: "relationship--19153106-5607-4cac-91a5-c2a900bc5343"
---
# Relationship 4603: S0126 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) has used a scheduled task to launch its PowerShell loader.(Citation: ESET ComRAT May 2020)(Citation: CISA ComRAT Oct 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19153106-5607-4cac-91a5-c2a900bc5343`.
