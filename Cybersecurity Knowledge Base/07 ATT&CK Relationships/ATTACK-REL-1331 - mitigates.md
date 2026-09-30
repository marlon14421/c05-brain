---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1030"
target_object: "T1565.003"
stix_relationship_id: "relationship--0f285d1e-eca9-4003-9a7f-454f3457e7ac"
---
# Relationship 1331: M1030 — mitigates → T1565.003

**Source object:** [[01 ATT&CK/M1030 - Network Segmentation|M1030: Network Segmentation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1565.003 - Runtime Data Manipulation|T1565.003: Runtime Data Manipulation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Identify critical business and system processes that may be targeted by adversaries and work to isolate and secure those systems against unauthorized access and tampering.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f285d1e-eca9-4003-9a7f-454f3457e7ac`.
