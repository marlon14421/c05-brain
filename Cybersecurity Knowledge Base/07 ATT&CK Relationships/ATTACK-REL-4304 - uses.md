---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0451"
target_object: "T1027.013"
stix_relationship_id: "relationship--2f96597c-70d9-41ba-b019-fb7510d3d732"
---
# Relationship 4304: S0451 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0451 - LoudMiner|S0451: LoudMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) has encrypted DMG files.(Citation: ESET LoudMiner June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f96597c-70d9-41ba-b019-fb7510d3d732`.
