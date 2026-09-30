---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0047"
target_object: "T1553.002"
stix_relationship_id: "relationship--1b1223a8-f8a4-46a9-af36-d71bfc6072b8"
---
# Relationship 4902: C0047 — uses → T1553.002

**Source object:** [[01 ATT&CK/C0047 - RedDelta Modified PlugX Infection Chain Operations|C0047: RedDelta Modified PlugX Infection Chain Operations]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) used legitimate, signed binaries such as `inkform.exe` or `ExcelRepairToolboxLauncher.exe` for follow-on execution of malicious DLLs through DLL search order hijacking in [RedDelta Modified PlugX Infection Chain Operations](https://attack.mitre.org/campaigns/C0047).(Citation: Recorded Future RedDelta 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b1223a8-f8a4-46a9-af36-d71bfc6072b8`.
