---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "S0626"
stix_relationship_id: "relationship--355d8ef4-ed79-49e4-b287-feb525d33ac4"
---
# Relationship 2960: G0045 — uses → S0626

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0626 - P8RAT|S0626: P8RAT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Securelist APT10 March 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--355d8ef4-ed79-49e4-b287-feb525d33ac4`.
