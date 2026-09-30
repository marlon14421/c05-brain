---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0337"
target_object: "T1074.001"
stix_relationship_id: "relationship--330e86f3-f4ff-4fe0-af64-cd3c86849239"
---
# Relationship 2849: S0337 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0337 - BadPatch|S0337: BadPatch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BadPatch](https://attack.mitre.org/software/S0337) stores collected data in log files before exfiltration.(Citation: Unit 42 BadPatch Oct 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--330e86f3-f4ff-4fe0-af64-cd3c86849239`.
