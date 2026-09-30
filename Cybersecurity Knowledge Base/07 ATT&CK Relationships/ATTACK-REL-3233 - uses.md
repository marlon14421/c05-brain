---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1141"
target_object: "T1001.002"
stix_relationship_id: "relationship--06f14692-8825-4947-9a63-fb4b4384b7ed"
---
# Relationship 3233: S1141 — uses → T1001.002

**Source object:** [[01 ATT&CK/S1141 - LunarWeb|S1141: LunarWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.002 - Steganography|T1001.002: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LunarWeb](https://attack.mitre.org/software/S1141) can receive C2 commands hidden in the structure of .jpg and .gif images.(Citation: ESET Turla Lunar toolset May 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06f14692-8825-4947-9a63-fb4b4384b7ed`.
