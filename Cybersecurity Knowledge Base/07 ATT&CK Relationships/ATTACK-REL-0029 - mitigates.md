---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1057"
target_object: "T1052"
stix_relationship_id: "relationship--17e06f95-da1f-4481-a586-9dfee23a26ed"
---
# Relationship 0029: M1057 — mitigates → T1052

**Source object:** [[01 ATT&CK/M1057 - Data Loss Prevention|M1057: Data Loss Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1052 - Exfiltration Over Physical Medium|T1052: Exfiltration Over Physical Medium]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Data loss prevention can detect and block sensitive data being copied to physical mediums.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17e06f95-da1f-4481-a586-9dfee23a26ed`.
