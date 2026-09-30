---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0332"
target_object: "T1491.001"
stix_relationship_id: "relationship--04b9d1e7-6deb-46f8-9fe3-9fb870ba8d72"
---
# Relationship 4148: S0332 — uses → T1491.001

**Source object:** [[01 ATT&CK/S0332 - Remcos|S0332: Remcos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1491.001 - Internal Defacement|T1491.001: Internal Defacement]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Remcos](https://attack.mitre.org/software/S0332) has the ability to modify the desktop wallpaper.(Citation: Fortinet Remcos Campaign NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04b9d1e7-6deb-46f8-9fe3-9fb870ba8d72`.
