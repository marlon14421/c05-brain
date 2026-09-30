---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1210"
target_object: "T1560.001"
stix_relationship_id: "relationship--e1ed817f-9fd5-4bea-92b5-9cc77e6f829b"
---
# Relationship 3071: S1210 — uses → T1560.001

**Source object:** [[01 ATT&CK/S1210 - Sagerunex|S1210: Sagerunex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sagerunex](https://attack.mitre.org/software/S1210) has archived collected materials in RAR format.(Citation: Cisco LotusBlossom 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1ed817f-9fd5-4bea-92b5-9cc77e6f829b`.
