---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0009"
target_object: "S0074"
stix_relationship_id: "relationship--70dc6b5c-c524-429e-a6ab-0dd40f0482c1"
---
# Relationship 4012: G0009 — uses → S0074

**Source object:** [[01 ATT&CK/G0009 - Deep Panda|G0009: Deep Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0074 - Sakula|S0074: Sakula]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: ThreatConnect Anthem)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70dc6b5c-c524-429e-a6ab-0dd40f0482c1`.
