---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1113"
stix_relationship_id: "relationship--a6f8439f-bf5a-4e57-8ae5-758e5097a0ff"
---
# Relationship 4550: S1148 — uses → T1113

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) can capture screenshots from victim systems.(Citation: S2W Racoon 2022)(Citation: Sekoia Raccoon2 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6f8439f-bf5a-4e57-8ae5-758e5097a0ff`.
