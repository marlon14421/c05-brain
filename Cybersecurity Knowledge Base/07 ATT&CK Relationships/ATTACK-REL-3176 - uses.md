---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1480"
stix_relationship_id: "relationship--0bd24ac6-08f1-441b-bb55-777e20799b17"
---
# Relationship 3176: S1239 — uses → T1480

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has an exception handler that executes when ESET antivirus applications `ekrn.exe` and `egui.exe` are not found and directly injects its code into waitfor.exe using Native Windows API including `WriteProcessMemory` and `CreateRemoteThreadEx`.(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0bd24ac6-08f1-441b-bb55-777e20799b17`.
