---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1100"
target_object: "T1095"
stix_relationship_id: "relationship--2302de7d-8c9a-4a92-93d3-e4b00c40b22d"
---
# Relationship 2887: S1100 — uses → T1095

**Source object:** [[01 ATT&CK/S1100 - Ninja|S1100: Ninja]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ninja](https://attack.mitre.org/software/S1100) can forward TCP packets between the C2 and a remote host.(Citation: Kaspersky ToddyCat June 2022)(Citation: Kaspersky ToddyCat Check Logs October 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2302de7d-8c9a-4a92-93d3-e4b00c40b22d`.
