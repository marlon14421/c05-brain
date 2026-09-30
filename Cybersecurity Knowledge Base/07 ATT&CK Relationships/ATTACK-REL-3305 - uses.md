---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1082"
stix_relationship_id: "relationship--670b59d4-25c6-4171-a36b-efb27155cc95"
---
# Relationship 3305: S9001 — uses → T1082

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has collected username , build number and serial number, then sent the information to the C2 server.(Citation: SophosGnGal_SystemBC_Dec2020)(Citation: AhnLab_SystemBC_Apr2022) [SystemBC](https://attack.mitre.org/software/S9001) has also gathered device name, operating system, and processor type.(Citation: HarmonProofpoint_SystemBC_Aug2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--670b59d4-25c6-4171-a36b-efb27155cc95`.
