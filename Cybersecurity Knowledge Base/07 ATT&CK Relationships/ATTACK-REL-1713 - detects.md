---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0473"
target_object: "T1543.005"
stix_relationship_id: "relationship--a0a7fa79-fe0a-4f2c-aa23-5bc18c1c4891"
---
# Relationship 1713: DET0473 — detects → T1543.005

**Source object:** [[01 ATT&CK/DET0473 - Detect persistent or elevated container services via container runtime or cluster man|DET0473: Detect persistent or elevated container services via container runtime or cluster manipulation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1543.005 - Container Service|T1543.005: Container Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0a7fa79-fe0a-4f2c-aa23-5bc18c1c4891`.
