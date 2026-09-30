---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0398"
target_object: "T1106"
stix_relationship_id: "relationship--bc8cb83f-fc66-4c44-8d60-f6f4be4b4f41"
---
# Relationship 3424: S0398 — uses → T1106

**Source object:** [[01 ATT&CK/S0398 - HyperBro|S0398: HyperBro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HyperBro](https://attack.mitre.org/software/S0398) has the ability to run an application ( CreateProcessW ) or script/file ( ShellExecuteW ) via API.(Citation: Unit42 Emissary Panda May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc8cb83f-fc66-4c44-8d60-f6f4be4b4f41`.
