---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0253"
target_object: "T1685.005"
stix_relationship_id: "relationship--c07f4012-d5dc-4039-9d5c-7487c501188f"
---
# Relationship 3960: S0253 — uses → T1685.005

**Source object:** [[01 ATT&CK/S0253 - RunningRAT|S0253: RunningRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RunningRAT](https://attack.mitre.org/software/S0253) contains code to clear event logs.(Citation: McAfee Gold Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c07f4012-d5dc-4039-9d5c-7487c501188f`.
