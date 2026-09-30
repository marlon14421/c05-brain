---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1497.001"
stix_relationship_id: "relationship--cbed7d53-5d5f-48ee-a2d0-ee10230d4e4c"
---
# Relationship 4282: S1086 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) has the ability to detect Windows Sandbox, VMWare, or VirtualBox by querying `Win32_ComputerSystem` to extract the `Manufacturer` string.(Citation: Morphisec Snip3 May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbed7d53-5d5f-48ee-a2d0-ee10230d4e4c`.
