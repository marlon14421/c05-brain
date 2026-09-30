---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0249"
target_object: "T1547.001"
stix_relationship_id: "relationship--750ca5b8-6142-46c0-9c40-f04dc9036bb9"
---
# Relationship 3024: S0249 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0249 - Gold Dragon|S0249: Gold Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gold Dragon](https://attack.mitre.org/software/S0249) establishes persistence in the Startup folder.(Citation: McAfee Gold Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--750ca5b8-6142-46c0-9c40-f04dc9036bb9`.
