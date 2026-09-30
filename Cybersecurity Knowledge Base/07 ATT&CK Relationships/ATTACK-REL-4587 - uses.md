---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0599"
target_object: "T1496.001"
stix_relationship_id: "relationship--fdf3767f-49ad-43f3-943c-486099ffa3a8"
---
# Relationship 4587: S0599 — uses → T1496.001

**Source object:** [[01 ATT&CK/S0599 - Kinsing|S0599: Kinsing]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1496.001 - Compute Hijacking|T1496.001: Compute Hijacking]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kinsing](https://attack.mitre.org/software/S0599) has created and run a Bitcoin cryptocurrency miner.(Citation: Aqua Kinsing April 2020)(Citation: Sysdig Kinsing November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdf3767f-49ad-43f3-943c-486099ffa3a8`.
