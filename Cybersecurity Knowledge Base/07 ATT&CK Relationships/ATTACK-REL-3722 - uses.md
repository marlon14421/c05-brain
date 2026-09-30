---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1064"
target_object: "T1497.001"
stix_relationship_id: "relationship--c29ef74c-0ddd-457a-b1e8-70793bbdda85"
---
# Relationship 3722: S1064 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1064 - SVCReady|S1064: SVCReady]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SVCReady](https://attack.mitre.org/software/S1064) has the ability to determine if its runtime environment is virtualized.(Citation: HP SVCReady Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c29ef74c-0ddd-457a-b1e8-70793bbdda85`.
