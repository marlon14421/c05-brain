---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1186"
target_object: "T1059.008"
stix_relationship_id: "relationship--c0369434-f35a-40e9-bd2e-21bba4ca20f7"
---
# Relationship 3040: S1186 — uses → T1059.008

**Source object:** [[01 ATT&CK/S1186 - Line Dancer|S1186: Line Dancer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.008 - Network Device CLI|T1059.008: Network Device CLI]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Line Dancer](https://attack.mitre.org/software/S1186) can execute native commands in networking device command line interfaces.(Citation: Cisco ArcaneDoor 2024)(Citation: CCCS ArcaneDoor 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0369434-f35a-40e9-bd2e-21bba4ca20f7`.
