---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1082"
stix_relationship_id: "relationship--cfc92bbe-4a8b-47ec-b12d-d08fdcea1fbb"
---
# Relationship 3026: S0240 — uses → T1082

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can gather the hostname and the OS version to ensure it doesn’t run on a Windows XP or Windows Server 2003 systems.(Citation: Talos ROKRAT)(Citation: Talos ROKRAT 2)(Citation: Securelist ScarCruft May 2019)(Citation: NCCGroup RokRat Nov 2018)(Citation: Volexity InkySquid RokRAT August 2021)(Citation: Malwarebytes RokRAT VBA January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfc92bbe-4a8b-47ec-b12d-d08fdcea1fbb`.
