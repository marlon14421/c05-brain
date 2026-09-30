---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1059.006"
stix_relationship_id: "relationship--cb58db80-48e9-4138-9ce4-bd726a3d1745"
---
# Relationship 4338: S0409 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Machete](https://attack.mitre.org/software/S0409) is written in Python and is used in conjunction with additional Python scripts.(Citation: ESET Machete July 2019)(Citation: Securelist Machete Aug 2014)(Citation: 360 Machete Sep 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb58db80-48e9-4138-9ce4-bd726a3d1745`.
