---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0215"
target_object: "T1102.002"
stix_relationship_id: "relationship--c2178e88-74c3-4bc6-b8c5-f6bbc95fc65a"
---
# Relationship 3751: S0215 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0215 - KARAE|S0215: KARAE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KARAE](https://attack.mitre.org/software/S0215) can use public cloud-based storage providers for command and control.(Citation: FireEye APT37 Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2178e88-74c3-4bc6-b8c5-f6bbc95fc65a`.
