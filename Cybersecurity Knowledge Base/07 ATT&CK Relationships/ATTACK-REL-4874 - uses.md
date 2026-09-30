---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0025"
target_object: "T1021.002"
stix_relationship_id: "relationship--f08b8e20-4dda-4ced-8e9d-f0a5e4ebcc52"
---
# Relationship 4874: C0025 — uses → T1021.002

**Source object:** [[01 ATT&CK/C0025 - 2016 Ukraine Electric Power Attack|C0025: 2016 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [2016 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0025), [Sandworm Team](https://attack.mitre.org/groups/G0034) utilized `net use` to connect to network shares.(Citation: Dragos Crashoverride 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f08b8e20-4dda-4ced-8e9d-f0a5e4ebcc52`.
