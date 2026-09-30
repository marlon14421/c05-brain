---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1039"
stix_relationship_id: "relationship--4716b9ec-a0d4-47db-a901-5a3b67d9e096"
---
# Relationship 3182: G0047 — uses → T1039

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1039 - Data from Network Shared Drive|T1039: Data from Network Shared Drive]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) malware has collected Microsoft Office documents from mapped network drives.(Citation: ESET Gamaredon June 2020)(Citation: ESET Gamaredon Sept2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4716b9ec-a0d4-47db-a901-5a3b67d9e096`.
