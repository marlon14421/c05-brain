---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0468"
target_object: "T1496.001"
stix_relationship_id: "relationship--0bb4fb8a-0b0f-46c6-820b-d46c5f98fa12"
---
# Relationship 3498: S0468 — uses → T1496.001

**Source object:** [[01 ATT&CK/S0468 - Skidmap|S0468: Skidmap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1496.001 - Compute Hijacking|T1496.001: Compute Hijacking]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Skidmap](https://attack.mitre.org/software/S0468) is a kernel-mode rootkit used for cryptocurrency mining.(Citation: Trend Micro Skidmap)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0bb4fb8a-0b0f-46c6-820b-d46c5f98fa12`.
