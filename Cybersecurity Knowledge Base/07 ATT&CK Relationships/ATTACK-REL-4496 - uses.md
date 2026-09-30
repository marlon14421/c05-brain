---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0066"
target_object: "S0205"
stix_relationship_id: "relationship--13c8251c-f380-425c-b762-2298e5802dee"
---
# Relationship 4496: G0066 — uses → S0205

**Source object:** [[01 ATT&CK/G0066 - Elderwood|G0066: Elderwood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0205 - Naid|S0205: Naid]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Symantec Elderwood Sept 2012)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13c8251c-f380-425c-b762-2298e5802dee`.
