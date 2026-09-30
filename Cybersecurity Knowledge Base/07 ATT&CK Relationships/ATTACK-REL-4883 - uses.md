---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0264"
target_object: "T1027.002"
stix_relationship_id: "relationship--d5c6c2bd-e49f-4d88-9351-a1c3d7f3ef99"
---
# Relationship 4883: S0264 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0264 - OopsIE|S0264: OopsIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OopsIE](https://attack.mitre.org/software/S0264) uses the SmartAssembly obfuscator to pack an embedded .Net Framework assembly used for C2.(Citation: Unit 42 OopsIE! Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5c6c2bd-e49f-4d88-9351-a1c3d7f3ef99`.
