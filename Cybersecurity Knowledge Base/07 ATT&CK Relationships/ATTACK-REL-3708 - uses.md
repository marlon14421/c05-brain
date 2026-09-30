---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1218.011"
stix_relationship_id: "relationship--797a925e-7fe8-4d88-a372-88160f24b111"
---
# Relationship 3708: S0559 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) used Rundll32 to execute payloads.(Citation: Microsoft Deep Dive Solorigate January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--797a925e-7fe8-4d88-a372-88160f24b111`.
