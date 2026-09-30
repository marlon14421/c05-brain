---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1100"
target_object: "T1082"
stix_relationship_id: "relationship--708161ff-7d5d-417a-83ad-d68ec6d4d01a"
---
# Relationship 4735: S1100 — uses → T1082

**Source object:** [[01 ATT&CK/S1100 - Ninja|S1100: Ninja]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ninja](https://attack.mitre.org/software/S1100) can obtain the computer name and information on the OS from targeted hosts.(Citation: Kaspersky ToddyCat June 2022)(Citation: Kaspersky ToddyCat Check Logs October 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--708161ff-7d5d-417a-83ad-d68ec6d4d01a`.
