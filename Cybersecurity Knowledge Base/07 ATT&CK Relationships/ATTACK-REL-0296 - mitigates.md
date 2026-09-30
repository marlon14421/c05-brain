---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1550.004"
stix_relationship_id: "relationship--10017b2e-7234-4368-81d7-a4c8b98c26a0"
---
# Relationship 0296: M1054 — mitigates → T1550.004

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550.004 - Web Session Cookie|T1550.004: Web Session Cookie]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Configure browsers or tasks to regularly delete persistent cookies.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10017b2e-7234-4368-81d7-a4c8b98c26a0`.
