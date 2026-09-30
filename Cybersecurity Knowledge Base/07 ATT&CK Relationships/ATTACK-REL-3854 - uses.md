---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1030"
target_object: "T1027.002"
stix_relationship_id: "relationship--c2266528-a862-4fc0-bfa1-4fb1d48daa56"
---
# Relationship 3854: S1030 — uses → T1027.002

**Source object:** [[01 ATT&CK/S1030 - Squirrelwaffle|S1030: Squirrelwaffle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Squirrelwaffle](https://attack.mitre.org/software/S1030) has been packed with a custom packer to hide payloads.(Citation: ZScaler Squirrelwaffle Sep 2021)(Citation: Netskope Squirrelwaffle Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2266528-a862-4fc0-bfa1-4fb1d48daa56`.
