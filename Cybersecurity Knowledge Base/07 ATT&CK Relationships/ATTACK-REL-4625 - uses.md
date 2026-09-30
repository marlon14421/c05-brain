---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0441"
target_object: "T1564.003"
stix_relationship_id: "relationship--dca41ced-2af1-4cec-8ed2-a1c77bc535ed"
---
# Relationship 4625: S0441 — uses → T1564.003

**Source object:** [[01 ATT&CK/S0441 - PowerShower|S0441: PowerShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerShower](https://attack.mitre.org/software/S0441) has added a registry key so future powershell.exe instances are spawned with coordinates for a window position off-screen by default.(Citation: Unit 42 Inception November 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dca41ced-2af1-4cec-8ed2-a1c77bc535ed`.
