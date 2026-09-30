---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1041"
target_object: "T1574.001"
stix_relationship_id: "relationship--05e15ff7-e0b1-47e3-a7bd-7f0e8845bf2c"
---
# Relationship 4612: S1041 — uses → T1574.001

**Source object:** [[01 ATT&CK/S1041 - Chinoxy|S1041: Chinoxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chinoxy](https://attack.mitre.org/software/S1041) can use a digitally signed binary ("Logitech Bluetooth Wizard Host Process") to load its dll into memory.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05e15ff7-e0b1-47e3-a7bd-7f0e8845bf2c`.
