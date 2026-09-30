---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1033"
target_object: "T1204"
stix_relationship_id: "relationship--a0919108-e327-4429-abc6-d251d78bd3a2"
---
# Relationship 1064: M1033 — mitigates → T1204

**Source object:** [[01 ATT&CK/M1033 - Limit Software Installation|M1033: Limit Software Installation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1204 - User Execution|T1204: User Execution]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Where possible, consider requiring developers to pull from internal repositories containing verified and approved packages rather than from external ones.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0919108-e327-4429-abc6-d251d78bd3a2`.
