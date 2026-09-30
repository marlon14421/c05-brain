---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1218.005"
stix_relationship_id: "relationship--f76be4ac-f342-4904-b50d-06e28b878011"
---
# Relationship 3948: G0047 — uses → T1218.005

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has used `mshta.exe` to execute malicious files.(Citation: Symantec Shuckworm January 2022)(Citation: unit42_gamaredon_dec2022)(Citation: ESET Gamaredon Sept2024)(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f76be4ac-f342-4904-b50d-06e28b878011`.
