---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1070.006"
stix_relationship_id: "relationship--f1e4c1ce-98d7-43fd-af33-f26f73aeca8b"
---
# Relationship 4056: S9024 — uses → T1070.006

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has updated the timestamp using the `touch` command.(Citation: CISA SPAWNCHIMERA RESURGE February 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1e4c1ce-98d7-43fd-af33-f26f73aeca8b`.
