---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0572"
target_object: "T1098.006"
stix_relationship_id: "relationship--0f766ce0-f259-48ce-bab7-4f7e03539caf"
---
# Relationship 1475: DET0572 — detects → T1098.006

**Source object:** [[01 ATT&CK/DET0572 - Suspicious RoleBinding or ClusterRoleBinding Assignment in Kubernetes|DET0572: Suspicious RoleBinding or ClusterRoleBinding Assignment in Kubernetes]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1098.006 - Additional Container Cluster Roles|T1098.006: Additional Container Cluster Roles]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f766ce0-f259-48ce-bab7-4f7e03539caf`.
