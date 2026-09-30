---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0398"
target_object: "T1027.013"
stix_relationship_id: "relationship--bda95df4-bf1d-4a49-b847-cf4f3fd5f51c"
---
# Relationship 3465: S0398 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0398 - HyperBro|S0398: HyperBro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HyperBro](https://attack.mitre.org/software/S0398) can be delivered encrypted to a compromised host.(Citation: Trend Micro DRBControl February 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bda95df4-bf1d-4a49-b847-cf4f3fd5f51c`.
