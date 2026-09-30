---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0155"
target_object: "T1095"
stix_relationship_id: "relationship--1984ba26-2309-49db-8c42-75951d0ef678"
---
# Relationship 3636: S0155 — uses → T1095

**Source object:** [[01 ATT&CK/S0155 - WINDSHIELD|S0155: WINDSHIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WINDSHIELD](https://attack.mitre.org/software/S0155) C2 traffic can communicate via TCP raw sockets.(Citation: FireEye APT32 May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1984ba26-2309-49db-8c42-75951d0ef678`.
