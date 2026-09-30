---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0565"
target_object: "T1036"
stix_relationship_id: "relationship--288d8f70-d2af-44f8-86c9-fb8c2cd5103f"
---
# Relationship 2693: S0565 — uses → T1036

**Source object:** [[01 ATT&CK/S0565 - Raindrop|S0565: Raindrop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raindrop](https://attack.mitre.org/software/S0565) was built to include a modified version of 7-Zip source code (including associated export names) and Far Manager source code.(Citation: Symantec RAINDROP January 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--288d8f70-d2af-44f8-86c9-fb8c2cd5103f`.
