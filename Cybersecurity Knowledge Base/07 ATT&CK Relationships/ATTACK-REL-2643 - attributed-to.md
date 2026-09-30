---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0052"
target_object: "G0004"
stix_relationship_id: "relationship--c1b3aa1d-ffc8-4ca9-8214-aa671c5d27f6"
---
# Relationship 2643: C0052 — attributed-to → G0004

**Source object:** [[01 ATT&CK/C0052 - SPACEHOP Activity|C0052: SPACEHOP Activity]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ORB Mandiant)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1b3aa1d-ffc8-4ca9-8214-aa671c5d27f6`.
