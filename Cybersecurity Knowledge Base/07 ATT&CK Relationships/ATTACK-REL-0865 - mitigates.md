---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1034"
target_object: "T1674"
stix_relationship_id: "relationship--2b1a2466-1698-46f1-a6f7-58d3b5cd892e"
---
# Relationship 0865: M1034 — mitigates → T1674

**Source object:** [[01 ATT&CK/M1034 - Limit Hardware Installation|M1034: Limit Hardware Installation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1674 - Input Injection|T1674: Input Injection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the use of USB devices and removable media within a network.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b1a2466-1698-46f1-a6f7-58d3b5cd892e`.
