---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0213"
target_object: "T1102.002"
stix_relationship_id: "relationship--c2fcdaf4-f4e7-446d-8b92-7a9df7ccc1f8"
---
# Relationship 4990: S0213 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0213 - DOGCALL|S0213: DOGCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DOGCALL](https://attack.mitre.org/software/S0213) is capable of leveraging cloud storage APIs such as Cloud, Box, Dropbox, and Yandex for C2.(Citation: FireEye APT37 Feb 2018)(Citation: Unit 42 Nokki Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2fcdaf4-f4e7-446d-8b92-7a9df7ccc1f8`.
