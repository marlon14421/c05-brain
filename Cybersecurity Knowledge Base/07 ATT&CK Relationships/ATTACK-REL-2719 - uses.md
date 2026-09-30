---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1198"
target_object: "T1059.004"
stix_relationship_id: "relationship--80ef6372-2983-48bf-b963-33592cdf8128"
---
# Relationship 2719: S1198 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) reads command line arguments and parses them for functionality when executed from a Linux shell, and can execute arbitrary strings passed to it as shell commands.(Citation: Symantec Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80ef6372-2983-48bf-b963-33592cdf8128`.
