---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1543.005"
stix_relationship_id: "relationship--c92e754c-48bf-4c8c-9504-47bd7f248baf"
---
# Relationship 1375: M1018 — mitigates → T1543.005

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1543.005 - Container Service|T1543.005: Container Service]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit access to utilities such as docker to only users who have a legitimate need, especially if using docker in rootful mode. In Kubernetes environments, only grant privileges to deploy pods to users that require it.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c92e754c-48bf-4c8c-9504-47bd7f248baf`.
