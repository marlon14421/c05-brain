---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1202"
target_object: "T1057"
stix_relationship_id: "relationship--c32cb7ce-20a0-43d9-b600-d44ef0254aa8"
---
# Relationship 4052: S1202 — uses → T1057

**Source object:** [[01 ATT&CK/S1202 - LockBit 3.0|S1202: LockBit 3.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LockBit 3.0](https://attack.mitre.org/software/S1202) can identify and terminate specific services.(Citation: Sentinel Labs LockBit 3.0 JUL 2022)(Citation: Joint Cybersecurity Advisory LockBit JUN 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c32cb7ce-20a0-43d9-b600-d44ef0254aa8`.
