---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1003.001"
stix_relationship_id: "relationship--c8db7b65-563d-47ba-9e06-cabdbade47e9"
---
# Relationship 2944: G0004 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) has dumped credentials, including by using [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Mandiant Operation Ke3chang November 2014)(Citation: NCC Group APT15 Alive and Strong)(Citation: Microsoft NICKEL December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8db7b65-563d-47ba-9e06-cabdbade47e9`.
