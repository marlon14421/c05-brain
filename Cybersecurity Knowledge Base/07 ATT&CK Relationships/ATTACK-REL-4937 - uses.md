---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0130"
target_object: "T1082"
stix_relationship_id: "relationship--02206f22-80e9-4f87-9e4b-5c1df1eb737e"
---
# Relationship 4937: S0130 — uses → T1082

**Source object:** [[01 ATT&CK/S0130 - Unknown Logger|S0130: Unknown Logger]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Unknown Logger](https://attack.mitre.org/software/S0130) can obtain information about the victim computer name, physical memory, country, and date.(Citation: Forcepoint Monsoon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02206f22-80e9-4f87-9e4b-5c1df1eb737e`.
