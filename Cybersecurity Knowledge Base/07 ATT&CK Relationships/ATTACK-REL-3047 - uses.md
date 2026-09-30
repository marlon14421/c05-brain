---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1100"
target_object: "T1559"
stix_relationship_id: "relationship--e4d5f735-1629-48f8-9728-f76adf586a0b"
---
# Relationship 3047: S1100 — uses → T1559

**Source object:** [[01 ATT&CK/S1100 - Ninja|S1100: Ninja]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ninja](https://attack.mitre.org/software/S1100) can use pipes to redirect the standard input and the standard output.(Citation: Kaspersky ToddyCat June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4d5f735-1629-48f8-9728-f76adf586a0b`.
