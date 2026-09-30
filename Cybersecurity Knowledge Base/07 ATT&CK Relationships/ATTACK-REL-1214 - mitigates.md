---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1484.002"
stix_relationship_id: "relationship--9336c4ae-22c1-4f45-bbba-5cf3f51553aa"
---
# Relationship 1214: M1018 — mitigates → T1484.002

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1484.002 - Trust Modification|T1484.002: Trust Modification]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

In cloud environments, limit permissions to create new identity providers to only those accounts that require them. In AWS environments, consider using Service Control policies to limit the use of API calls such as `CreateSAMLProvider` or `CreateOpenIDConnectProvider`.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9336c4ae-22c1-4f45-bbba-5cf3f51553aa`.
