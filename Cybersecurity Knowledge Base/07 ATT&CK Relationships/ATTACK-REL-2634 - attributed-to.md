---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0060"
target_object: "G1054"
stix_relationship_id: "relationship--2611f491-1c9d-4c2a-82da-8a9bcfc31870"
---
# Relationship 2634: C0060 — attributed-to → G1054

**Source object:** [[01 ATT&CK/C0060 - Operation AkaiRyū|C0060: Operation AkaiRyū]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: Trend Micro Earth Kasha Anel NOV 2024)(Citation: ESET MirrorFace 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2611f491-1c9d-4c2a-82da-8a9bcfc31870`.
