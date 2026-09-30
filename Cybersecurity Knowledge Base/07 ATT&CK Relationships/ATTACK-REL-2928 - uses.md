---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1230"
target_object: "T1574.001"
stix_relationship_id: "relationship--d6361b85-f248-462c-a0d4-409c04dadeb5"
---
# Relationship 2928: S1230 — uses → T1574.001

**Source object:** [[01 ATT&CK/S1230 - HIUPAN|S1230: HIUPAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HIUPAN](https://attack.mitre.org/software/S1230) has abused legitimate executables to side-load malicious DLLs to include the legitimate exe UsbConfig.exe.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6361b85-f248-462c-a0d4-409c04dadeb5`.
