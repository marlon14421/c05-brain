---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1048"
target_object: "T1021.003"
stix_relationship_id: "relationship--7566cba1-7be8-4647-b0ab-2991fcde2abf"
---
# Relationship 0253: M1048 — mitigates → T1021.003

**Source object:** [[01 ATT&CK/M1048 - Application Isolation and Sandboxing|M1048: Application Isolation and Sandboxing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.003 - Distributed Component Object Model|T1021.003: Distributed Component Object Model]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure all COM alerts and Protected View are enabled.(Citation: Microsoft Protected View)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7566cba1-7be8-4647-b0ab-2991fcde2abf`.
