---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "T1482"
stix_relationship_id: "relationship--1002e4b9-a9c0-403d-ad81-692b34474dc0"
---
# Relationship 4741: G1043 — uses → T1482

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) enumerated Active Directory information and trust relationships during operations.(Citation: FBI BlackByte 2022)(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1002e4b9-a9c0-403d-ad81-692b34474dc0`.
