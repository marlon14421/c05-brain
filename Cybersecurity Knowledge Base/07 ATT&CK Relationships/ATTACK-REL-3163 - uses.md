---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1090"
target_object: "T1074.001"
stix_relationship_id: "relationship--d8c447e8-6581-47ca-98d6-44b262023669"
---
# Relationship 3163: S1090 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1090 - NightClub|S1090: NightClub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NightClub](https://attack.mitre.org/software/S1090) has copied captured files and keystrokes to the `%TEMP%` directory of compromised hosts.(Citation: MoustachedBouncer ESET August 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8c447e8-6581-47ca-98d6-44b262023669`.
