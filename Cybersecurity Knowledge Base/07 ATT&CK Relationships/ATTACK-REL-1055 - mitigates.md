---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1482"
stix_relationship_id: "relationship--047e6dc3-d213-4d97-8573-9c8da28a0742"
---
# Relationship 1055: M1047 — mitigates → T1482

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Map the trusts within existing domains/forests and keep trust relationships to a minimum.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--047e6dc3-d213-4d97-8573-9c8da28a0742`.
