---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1129"
stix_relationship_id: "relationship--2c89cab1-efbb-405c-930d-197ae1910e5b"
---
# Relationship 0835: M1038 — mitigates → T1129

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Identify and block potentially malicious software executed through this technique by using application control tools capable of preventing unknown modules from being loaded.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c89cab1-efbb-405c-930d-197ae1910e5b`.
