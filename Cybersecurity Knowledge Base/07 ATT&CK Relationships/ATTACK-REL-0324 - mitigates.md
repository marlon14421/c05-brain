---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1059.013"
stix_relationship_id: "relationship--58743d1b-6abb-43dd-8fcc-9da1082386e0"
---
# Relationship 0324: M1026 — mitigates → T1059.013

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.013 - Container CLI-API|T1059.013: Container CLI/API]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Restrict permissions on API access. RBAC in Kubernetes involve permissions that are additive, meaning there are no explicit "deny" rules. These permissions can be defined within a particular namespace or within cluster-scoped resources. Securing the Docker daemon can be done by using SSH or TLS with certificate authorization. Container management tools such as Docker and Podman may offer ways to run containers as rootless, which prevents them from running with privileged permissions.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58743d1b-6abb-43dd-8fcc-9da1082386e0`.
