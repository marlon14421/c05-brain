---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1552.007"
stix_relationship_id: "relationship--803c83dc-fe82-40e4-8aa7-35c95269ef8f"
---
# Relationship 0850: M1026 — mitigates → T1552.007

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1552.007 - Container API|T1552.007: Container API]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use the principle of least privilege for privileged accounts such as the service account in Kubernetes. For example, if a pod is not required to access the Kubernetes API, consider disabling the service account altogether.(Citation: Kubernetes Service Accounts)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--803c83dc-fe82-40e4-8aa7-35c95269ef8f`.
