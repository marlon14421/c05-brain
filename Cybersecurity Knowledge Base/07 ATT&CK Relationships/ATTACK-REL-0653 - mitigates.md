---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1036.001"
stix_relationship_id: "relationship--3e646993-2414-4382-b709-6c5bc02740e3"
---
# Relationship 0653: M1045 — mitigates → T1036.001

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1036.001 - Invalid Code Signature|T1036.001: Invalid Code Signature]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Require signed binaries.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e646993-2414-4382-b709-6c5bc02740e3`.
