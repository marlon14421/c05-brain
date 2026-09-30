---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1106"
stix_relationship_id: "relationship--d55c917d-0728-4e09-a58b-672094786e40"
---
# Relationship 3538: S1239 — uses → T1106

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has utilized Native Windows API functions such as `WriteProcessMemory` and `CreateRemoteThreadEx`.(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025) [TONESHELL](https://attack.mitre.org/software/S1239) has also utilized Windows API functions for creating seed values including `CoCreateGuid` and `GetTickCount`.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Zscaler) [TONESHELL](https://attack.mitre.org/software/S1239) has leveraged the legitimate API function `EnumSystemLocalesA` to run its shellcode through the callback function.(Citation: Palo Alto Networks, Unit 42)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d55c917d-0728-4e09-a58b-672094786e40`.
