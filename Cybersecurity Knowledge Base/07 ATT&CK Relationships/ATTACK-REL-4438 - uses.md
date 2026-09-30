---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1022"
target_object: "T1074.002"
stix_relationship_id: "relationship--c710daae-cde1-4170-ae45-4910b3187cd8"
---
# Relationship 4438: G1022 — uses → T1074.002

**Source object:** [[01 ATT&CK/G1022 - ToddyCat|G1022: ToddyCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.002 - Remote Data Staging|T1074.002: Remote Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ToddyCat](https://attack.mitre.org/groups/G1022) manually transferred collected files to an exfiltration host using xcopy.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c710daae-cde1-4170-ae45-4910b3187cd8`.
