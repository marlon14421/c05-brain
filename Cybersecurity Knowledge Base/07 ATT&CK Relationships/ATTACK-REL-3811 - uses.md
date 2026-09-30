---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1102.003"
stix_relationship_id: "relationship--68e18f32-aae3-4bd6-b8e5-6ec2ec3d4173"
---
# Relationship 3811: S0455 — uses → T1102.003

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.003 - One-Way Communication|T1102.003: One-Way Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has downloaded a zip file for execution on the system.(Citation: Medium Metamorfo Apr 2020)(Citation: FireEye Metamorfo Apr 2018)(Citation: Fortinet Metamorfo Feb 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68e18f32-aae3-4bd6-b8e5-6ec2ec3d4173`.
