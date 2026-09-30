---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1497"
stix_relationship_id: "relationship--c9a7b01c-5ba6-41db-944a-ed5ba8531398"
---
# Relationship 4715: S0147 — uses → T1497

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) has the ability to use anti-detection functions to identify sandbox environments.(Citation: Unit 42 Gamaredon February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9a7b01c-5ba6-41db-944a-ed5ba8531398`.
