---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0167"
target_object: "T1113"
stix_relationship_id: "relationship--a56aafe6-4a54-4ce5-b927-8b56826b3445"
---
# Relationship 2825: S0167 — uses → T1113

**Source object:** [[01 ATT&CK/S0167 - Matryoshka|S0167: Matryoshka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Matryoshka](https://attack.mitre.org/software/S0167) is capable of performing screen captures.(Citation: ClearSky Wilted Tulip July 2017)(Citation: CopyKittens Nov 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a56aafe6-4a54-4ce5-b927-8b56826b3445`.
