---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1218.003"
stix_relationship_id: "relationship--5dbd040e-0433-42ca-8e03-b3741be31cb2"
---
# Relationship 3885: G0080 — uses → T1218.003

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.003 - CMSTP|T1218.003: CMSTP]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) has used the command cmstp.exe /s /ns C:\Users\ADMINI~W\AppData\Local\Temp\XKNqbpzl.txt to bypass AppLocker and launch a malicious script.(Citation: Talos Cobalt Group July 2018)(Citation: Morphisec Cobalt Gang Oct 2018)(Citation: Unit 42 Cobalt Gang Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5dbd040e-0433-42ca-8e03-b3741be31cb2`.
