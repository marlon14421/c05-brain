---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1518.001"
stix_relationship_id: "relationship--ffb03265-d9d6-4dc7-ba8e-71498be4e131"
---
# Relationship 2653: G0106 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) used scripts which detected and uninstalled antivirus software.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffb03265-d9d6-4dc7-ba8e-71498be4e131`.
