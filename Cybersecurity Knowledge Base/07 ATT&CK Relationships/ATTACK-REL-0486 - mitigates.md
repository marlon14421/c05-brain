---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1059.009"
stix_relationship_id: "relationship--bf5fcae9-bc18-4278-bf0c-be7237a5d8eb"
---
# Relationship 0486: M1026 — mitigates → T1059.009

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.009 - Cloud API|T1059.009: Cloud API]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use of proper Identity and Access Management (IAM) with Role Based Access Control (RBAC) policies to limit actions administrators can perform and provide a history of administrative actions to detect unauthorized use and abuse.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf5fcae9-bc18-4278-bf0c-be7237a5d8eb`.
