---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9029"
target_object: "T1071.001"
stix_relationship_id: "relationship--384a2f71-38aa-49b8-868f-f7888d205314"
---
# Relationship 3959: S9029 — uses → T1071.001

**Source object:** [[01 ATT&CK/S9029 - IronWind|S9029: IronWind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IronWind](https://attack.mitre.org/software/S9029) can used HTTP to send information to C2 about the targeted system.(Citation: Check Point Wirte NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--384a2f71-38aa-49b8-868f-f7888d205314`.
