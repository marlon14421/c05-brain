---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1069"
stix_relationship_id: "relationship--34a06e23-b81c-45c7-96bc-7e08d31a4a44"
---
# Relationship 2912: S0483 — uses → T1069

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has the ability to identify Workgroup membership.(Citation: IBM IcedID November 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34a06e23-b81c-45c7-96bc-7e08d31a4a44`.
