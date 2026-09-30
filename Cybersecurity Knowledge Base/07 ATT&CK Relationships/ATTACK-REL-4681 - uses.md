---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0284"
target_object: "T1059.003"
stix_relationship_id: "relationship--3524e5ae-332f-4e53-8129-e638961cc38e"
---
# Relationship 4681: S0284 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0284 - More_eggs|S0284: More_eggs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[More_eggs](https://attack.mitre.org/software/S0284) has used cmd.exe for execution.(Citation: Security Intelligence More Eggs Aug 2019)(Citation: ESET EvilNum July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3524e5ae-332f-4e53-8129-e638961cc38e`.
