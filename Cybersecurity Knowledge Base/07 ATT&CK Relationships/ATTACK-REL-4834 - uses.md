---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1075"
target_object: "T1057"
stix_relationship_id: "relationship--63cefb36-bc55-4536-b7f9-c80f9e3f69b3"
---
# Relationship 4834: S1075 — uses → T1057

**Source object:** [[01 ATT&CK/S1075 - KOPILUWAK|S1075: KOPILUWAK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KOPILUWAK](https://attack.mitre.org/software/S1075) can enumerate current running processes on the targeted machine.(Citation: Mandiant Suspected Turla Campaign February 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63cefb36-bc55-4536-b7f9-c80f9e3f69b3`.
