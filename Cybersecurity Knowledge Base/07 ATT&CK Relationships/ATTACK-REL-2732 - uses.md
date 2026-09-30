---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9037"
target_object: "T1547.001"
stix_relationship_id: "relationship--600e55f7-1a72-4289-9c4c-b66798a58776"
---
# Relationship 2732: S9037 — uses → T1547.001

**Source object:** [[01 ATT&CK/S9037 - RustyWater|S9037: RustyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) has established persistence by adding `C:\ProgramData\CertificationKit.ini` to a Windows startup Registry key or to a Run or RunOnce Registry key.(Citation: CloudSEK_RustyWater_Jan2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--600e55f7-1a72-4289-9c4c-b66798a58776`.
