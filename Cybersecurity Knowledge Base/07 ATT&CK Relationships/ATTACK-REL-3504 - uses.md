---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0045"
target_object: "T1588.002"
stix_relationship_id: "relationship--7e2a54af-5e8f-4431-810d-7fcaa4c1eca0"
---
# Relationship 3504: C0045 — uses → T1588.002

**Source object:** [[01 ATT&CK/C0045 - ShadowRay|C0045: ShadowRay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [ShadowRay](https://attack.mitre.org/campaigns/C0045), threat actors used tools including the XMRig miner and Interactsh.(Citation: Oligo ShadowRay Campaign MAR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e2a54af-5e8f-4431-810d-7fcaa4c1eca0`.
