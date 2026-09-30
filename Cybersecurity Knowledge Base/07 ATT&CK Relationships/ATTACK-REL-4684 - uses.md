---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0468"
target_object: "T1518.001"
stix_relationship_id: "relationship--49f761f9-89d2-4e6f-a0c6-fc5e32cca471"
---
# Relationship 4684: S0468 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0468 - Skidmap|S0468: Skidmap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Skidmap](https://attack.mitre.org/software/S0468) has the ability to check if /usr/sbin/setenforce exists. This file controls what mode SELinux is in.(Citation: Trend Micro Skidmap)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49f761f9-89d2-4e6f-a0c6-fc5e32cca471`.
