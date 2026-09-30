---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "S0195"
stix_relationship_id: "relationship--67ad06ba-8fcc-490e-95fd-7322a97136f1"
---
# Relationship 3085: G0034 — uses → S0195

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0195 - SDelete|S0195: SDelete]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used [SDelete](https://attack.mitre.org/software/S0195) for wartime operations in 2022-2023.(Citation: mandiant_apt44_unearthing_sandworm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67ad06ba-8fcc-490e-95fd-7322a97136f1`.
