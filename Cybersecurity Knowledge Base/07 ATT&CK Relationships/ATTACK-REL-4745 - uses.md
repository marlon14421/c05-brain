---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1559"
stix_relationship_id: "relationship--d5b2d34f-5650-4fb3-bacf-2b1765943bfe"
---
# Relationship 4745: S1078 — uses → T1559

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

When executing with non-root permissions, [RotaJakiro](https://attack.mitre.org/software/S1078) uses the the `shmget API` to create shared memory between other known [RotaJakiro](https://attack.mitre.org/software/S1078) processes. This allows processes to communicate with each other and share their PID.(Citation: RotaJakiro 2021 netlab360 analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5b2d34f-5650-4fb3-bacf-2b1765943bfe`.
