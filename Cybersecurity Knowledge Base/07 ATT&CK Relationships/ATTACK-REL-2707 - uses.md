---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0112"
target_object: "T1542.003"
stix_relationship_id: "relationship--44b56e08-7cd1-442c-8806-c69bb65fd231"
---
# Relationship 2707: S0112 — uses → T1542.003

**Source object:** [[01 ATT&CK/S0112 - ROCKBOOT|S0112: ROCKBOOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1542.003 - Bootkit|T1542.003: Bootkit]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROCKBOOT](https://attack.mitre.org/software/S0112) is a Master Boot Record (MBR) bootkit that uses the MBR to establish persistence.(Citation: FireEye Bootkits)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44b56e08-7cd1-442c-8806-c69bb65fd231`.
