---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1141"
target_object: "T1082"
stix_relationship_id: "relationship--0ed59ea2-85bb-4633-9b55-9e322dcbbd83"
---
# Relationship 4411: S1141 — uses → T1082

**Source object:** [[01 ATT&CK/S1141 - LunarWeb|S1141: LunarWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LunarWeb](https://attack.mitre.org/software/S1141) can use WMI queries and shell commands such as systeminfo.exe to collect the operating system, BIOS version, and domain name of the targeted system.(Citation: ESET Turla Lunar toolset May 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ed59ea2-85bb-4633-9b55-9e322dcbbd83`.
