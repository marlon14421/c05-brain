---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0262"
target_object: "T1552.001"
stix_relationship_id: "relationship--a628def4-31a4-475e-b4b8-615534d8d585"
---
# Relationship 3094: S0262 — uses → T1552.001

**Source object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QuasarRAT](https://attack.mitre.org/software/S0262) can obtain passwords from FTP clients.(Citation: GitHub QuasarRAT)(Citation: Volexity Patchwork June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a628def4-31a4-475e-b4b8-615534d8d585`.
