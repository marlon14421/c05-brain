---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1036"
target_object: "T1550"
stix_relationship_id: "relationship--71f51186-1805-4108-bde1-5f999de8603d"
---
# Relationship 1269: M1036 — mitigates → T1550

**Source object:** [[01 ATT&CK/M1036 - Account Use Policies|M1036: Account Use Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550 - Use Alternate Authentication Material|T1550: Use Alternate Authentication Material]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Where possible, consider restricting the use of authentication material outside of expected contexts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71f51186-1805-4108-bde1-5f999de8603d`.
