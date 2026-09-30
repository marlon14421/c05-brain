---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0686"
target_object: "T1071.001"
stix_relationship_id: "relationship--142307da-c957-49ff-985f-9dd503c8626b"
---
# Relationship 3399: S0686 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0686 - QuietSieve|S0686: QuietSieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QuietSieve](https://attack.mitre.org/software/S0686) can use HTTPS in C2 communications.(Citation: Microsoft Actinium February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--142307da-c957-49ff-985f-9dd503c8626b`.
