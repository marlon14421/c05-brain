---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0344"
target_object: "T1057"
stix_relationship_id: "relationship--f503ea13-d045-4246-9674-a73f7e52ea85"
---
# Relationship 4454: S0344 — uses → T1057

**Source object:** [[01 ATT&CK/S0344 - Azorult|S0344: Azorult]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Azorult](https://attack.mitre.org/software/S0344) can collect a list of running processes by calling CreateToolhelp32Snapshot.(Citation: Unit42 Azorult Nov 2018)(Citation: Proofpoint Azorult July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f503ea13-d045-4246-9674-a73f7e52ea85`.
