---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0157"
target_object: "T1112"
stix_relationship_id: "relationship--6592447f-31c8-46d0-8e88-47584fa301f0"
---
# Relationship 4833: S0157 — uses → T1112

**Source object:** [[01 ATT&CK/S0157 - SOUNDBITE|S0157: SOUNDBITE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SOUNDBITE](https://attack.mitre.org/software/S0157) is capable of modifying the Registry.(Citation: FireEye APT32 May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6592447f-31c8-46d0-8e88-47584fa301f0`.
