---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1027.002"
stix_relationship_id: "relationship--1f9e644f-1ec9-4d2d-a475-3fca1bceaf20"
---
# Relationship 3915: S1196 — uses → T1027.002

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) has been delivered as a VMProtect-packed binary.(Citation: S2W Troll Stealer 2024)(Citation: ASEC Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f9e644f-1ec9-4d2d-a475-3fca1bceaf20`.
