---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1060"
target_object: "T1095"
stix_relationship_id: "relationship--3f424011-cde1-4ed5-b067-3cb4d6193d72"
---
# Relationship 4537: S1060 — uses → T1095

**Source object:** [[01 ATT&CK/S1060 - Mafalda|S1060: Mafalda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mafalda](https://attack.mitre.org/software/S1060) can use raw TCP for C2.(Citation: SentinelLabs Metador Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f424011-cde1-4ed5-b067-3cb4d6193d72`.
