---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1584.008"
stix_relationship_id: "relationship--1e81cdcc-e258-479f-9588-3649509bfcd1"
---
# Relationship 4458: G1017 — uses → T1584.008

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has compromised small office and home office (SOHO) network edge devices, many of which were located in the same geographic area as the victim, to proxy network traffic.(Citation: Microsoft Volt Typhoon May 2023)(Citation: Joint Cybersecurity Advisory Volt Typhoon June 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e81cdcc-e258-479f-9588-3649509bfcd1`.
