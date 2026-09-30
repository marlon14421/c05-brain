---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "S1058"
stix_relationship_id: "relationship--500bb3d4-9c5e-4020-b173-1a83e5ce1c3c"
---
# Relationship 4750: G0034 — uses → S1058

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1058 - Prestige|S1058: Prestige]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Microsoft Prestige ransomware October 2022)(Citation: mandiant_apt44_unearthing_sandworm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--500bb3d4-9c5e-4020-b173-1a83e5ce1c3c`.
