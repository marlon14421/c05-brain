---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1017"
target_object: "T1071.001"
stix_relationship_id: "relationship--d5ebb264-c9ae-44bb-b6d0-5bf490cb2f76"
---
# Relationship 4711: S1017 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1017 - OutSteel|S1017: OutSteel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OutSteel](https://attack.mitre.org/software/S1017) has used HTTP for C2 communications.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5ebb264-c9ae-44bb-b6d0-5bf490cb2f76`.
