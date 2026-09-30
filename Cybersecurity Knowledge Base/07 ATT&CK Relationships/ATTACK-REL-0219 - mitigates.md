---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1098.006"
stix_relationship_id: "relationship--af3fe271-9d63-447d-bd88-f5f0b41a43c2"
---
# Relationship 0219: M1032 — mitigates → T1098.006

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.006 - Additional Container Cluster Roles|T1098.006: Additional Container Cluster Roles]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Require multi-factor authentication for user accounts integrated into container clusters through cloud deployments or via authentication protocols such as LDAP or SAML.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af3fe271-9d63-447d-bd88-f5f0b41a43c2`.
