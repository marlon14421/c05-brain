---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0159"
target_object: "T1547.001"
stix_relationship_id: "relationship--c75cc595-79d7-4a77-9647-d2323aad93d0"
---
# Relationship 4722: S0159 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0159 - SNUGRIDE|S0159: SNUGRIDE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SNUGRIDE](https://attack.mitre.org/software/S0159) establishes persistence through a Registry Run key.(Citation: FireEye APT10 April 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c75cc595-79d7-4a77-9647-d2323aad93d0`.
