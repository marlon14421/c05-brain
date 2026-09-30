---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1016.001"
stix_relationship_id: "relationship--5fc69974-db3b-4475-b37b-07c4731b1a6f"
---
# Relationship 4744: G0047 — uses → T1016.001

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.001 - Internet Connection Discovery|T1016.001: Internet Connection Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has tested connectivity between a compromised machine and a C2 server using [Ping](https://attack.mitre.org/software/S0097) with commands such as `CSIDL_SYSTEM\cmd.exe /c ping -n 1`.(Citation: Symantec Shuckworm January 2022) [Gamaredon Group](https://attack.mitre.org/groups/G0047) has searched the ping records to obtain the C2 address and has used ping to search for the C2’s status.(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5fc69974-db3b-4475-b37b-07c4731b1a6f`.
