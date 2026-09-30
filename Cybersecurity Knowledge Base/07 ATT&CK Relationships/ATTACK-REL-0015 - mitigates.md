---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1555.006"
stix_relationship_id: "relationship--04724f1d-f6ff-448e-bcac-4bcda34d895b"
---
# Relationship 0015: M1026 — mitigates → T1555.006

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1555.006 - Cloud Secrets Management Stores|T1555.006: Cloud Secrets Management Stores]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the number of cloud accounts and services with permission to query the secrets manager to only those required. Ensure that accounts and services with permissions to query the secrets manager only have access to the secrets they require.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04724f1d-f6ff-448e-bcac-4bcda34d895b`.
