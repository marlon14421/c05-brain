---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1033"
target_object: "T1059.006"
stix_relationship_id: "relationship--9e0a19f8-e970-49a1-9952-ae7380247ace"
---
# Relationship 0196: M1033 — mitigates → T1059.006

**Source object:** [[01 ATT&CK/M1033 - Limit Software Installation|M1033: Limit Software Installation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent users from installing Python where not required.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e0a19f8-e970-49a1-9952-ae7380247ace`.
