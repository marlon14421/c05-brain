---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1227"
target_object: "T1124"
stix_relationship_id: "relationship--6e9690c6-f3d0-476a-969e-9d56e12c8b95"
---
# Relationship 4561: S1227 — uses → T1124

**Source object:** [[01 ATT&CK/S1227 - StarProxy|S1227: StarProxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) has utilized the windows API call `GetLocalTime()` to retrieve a SystemTime structure to generate a seed value.(Citation: Zscaler)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e9690c6-f3d0-476a-969e-9d56e12c8b95`.
