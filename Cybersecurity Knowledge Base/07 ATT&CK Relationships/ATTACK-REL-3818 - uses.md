---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1037"
target_object: "T1074.001"
stix_relationship_id: "relationship--f2d62173-bd89-4d00-bcb6-5e4f6fa43df2"
---
# Relationship 3818: S1037 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1037 - STARWHALE|S1037: STARWHALE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[STARWHALE](https://attack.mitre.org/software/S1037) has stored collected data in a file called `stari.txt`.(Citation: Mandiant UNC3313 Feb 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2d62173-bd89-4d00-bcb6-5e4f6fa43df2`.
