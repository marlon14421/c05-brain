---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1176.002"
stix_relationship_id: "relationship--16a6739b-93e9-49ea-ae74-624623d3c07a"
---
# Relationship 1053: M1038 — mitigates → T1176.002

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1176.002 - IDE Extensions|T1176.002: IDE Extensions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Set an IDE extension allow or deny list as appropriate for your security policy.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16a6739b-93e9-49ea-ae74-624623d3c07a`.
