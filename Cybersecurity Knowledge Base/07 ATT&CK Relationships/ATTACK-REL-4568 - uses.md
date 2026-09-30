---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1034"
target_object: "S1016"
stix_relationship_id: "relationship--38481000-2a88-4768-98a3-aab3c747a6d6"
---
# Relationship 4568: G1034 — uses → S1016

**Source object:** [[01 ATT&CK/G1034 - Daggerfly|G1034: Daggerfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1016 - MacMa|S1016: MacMa]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Daggerfly](https://attack.mitre.org/groups/G1034) is linked to the use and potentially development of [MacMa](https://attack.mitre.org/software/S1016) through overlapping command and control infrastructure and shared libraries with other unique tools.(Citation: Symantec Daggerfly 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38481000-2a88-4768-98a3-aab3c747a6d6`.
