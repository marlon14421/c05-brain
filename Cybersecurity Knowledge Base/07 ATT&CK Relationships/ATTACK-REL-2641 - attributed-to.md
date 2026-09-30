---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0047"
target_object: "G0129"
stix_relationship_id: "relationship--88015217-a3df-4654-bea1-b1d8241b67ee"
---
# Relationship 2641: C0047 — attributed-to → G0129

**Source object:** [[01 ATT&CK/C0047 - RedDelta Modified PlugX Infection Chain Operations|C0047: RedDelta Modified PlugX Infection Chain Operations]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[RedDelta Modified PlugX Infection Chain Operations](https://attack.mitre.org/campaigns/C0047) was an campaign linked to [Mustang Panda](https://attack.mitre.org/groups/G0129) operations.(Citation: Recorded Future RedDelta 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88015217-a3df-4654-bea1-b1d8241b67ee`.
