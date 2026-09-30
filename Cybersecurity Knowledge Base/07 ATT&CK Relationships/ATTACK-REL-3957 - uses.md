---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0660"
target_object: "T1574.001"
stix_relationship_id: "relationship--f044fed9-e7d4-4cb2-938b-d89fd8b0c06c"
---
# Relationship 3957: S0660 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0660 - Clambling|S0660: Clambling]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Clambling](https://attack.mitre.org/software/S0660) can store a file named `mpsvc.dll`, which opens a malicious `mpsvc.mui` file, in the same folder as the legitimate Microsoft executable `MsMpEng.exe` to gain execution.(Citation: Trend Micro DRBControl February 2020)(Citation: Talent-Jump Clambling February 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f044fed9-e7d4-4cb2-938b-d89fd8b0c06c`.
