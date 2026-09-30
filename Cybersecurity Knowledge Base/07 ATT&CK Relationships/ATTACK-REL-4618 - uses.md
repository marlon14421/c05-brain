---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1042"
target_object: "T1071.001"
stix_relationship_id: "relationship--0dec56fa-b975-4575-ac3c-0afc48b579d8"
---
# Relationship 4618: G1042 — uses → T1071.001

**Source object:** [[01 ATT&CK/G1042 - RedEcho|G1042: RedEcho]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedEcho](https://attack.mitre.org/groups/G1042) network activity is associated with SSL traffic via TCP 443 and proxied HTTP traffic over non-standard ports.(Citation: RecordedFuture RedEcho 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dec56fa-b975-4575-ac3c-0afc48b579d8`.
