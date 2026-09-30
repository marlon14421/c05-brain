---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0448"
target_object: "T1106"
stix_relationship_id: "relationship--ed3539fa-7ae7-45b0-9f0f-d62460ed07b1"
---
# Relationship 3064: S0448 — uses → T1106

**Source object:** [[01 ATT&CK/S0448 - Rising Sun|S0448: Rising Sun]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rising Sun](https://attack.mitre.org/software/S0448) used dynamic API resolutions to various Windows APIs by leveraging `LoadLibrary()` and `GetProcAddress()`.(Citation: McAfee Sharpshooter December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed3539fa-7ae7-45b0-9f0f-d62460ed07b1`.
