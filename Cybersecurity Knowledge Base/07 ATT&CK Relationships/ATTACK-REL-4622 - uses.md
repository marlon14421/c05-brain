---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0488"
target_object: "T1003.003"
stix_relationship_id: "relationship--10ecbc19-10ab-4564-a637-cc4f6773e533"
---
# Relationship 4622: S0488 — uses → T1003.003

**Source object:** [[01 ATT&CK/S0488 - CrackMapExec|S0488: CrackMapExec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CrackMapExec](https://attack.mitre.org/software/S0488) can dump hashed passwords associated with Active Directory using Windows' Directory Replication Services API (DRSUAPI), or Volume Shadow Copy.(Citation: CME Github September 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10ecbc19-10ab-4564-a637-cc4f6773e533`.
