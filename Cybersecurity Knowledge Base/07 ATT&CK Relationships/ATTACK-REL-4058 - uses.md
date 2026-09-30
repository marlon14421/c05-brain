---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0618"
target_object: "T1135"
stix_relationship_id: "relationship--422b117a-9cb1-4d03-9b2d-000de5d8526e"
---
# Relationship 4058: S0618 — uses → T1135

**Source object:** [[01 ATT&CK/S0618 - FIVEHANDS|S0618: FIVEHANDS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIVEHANDS](https://attack.mitre.org/software/S0618) can enumerate network shares and mounted drives on a network.(Citation: NCC Group Fivehands June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--422b117a-9cb1-4d03-9b2d-000de5d8526e`.
