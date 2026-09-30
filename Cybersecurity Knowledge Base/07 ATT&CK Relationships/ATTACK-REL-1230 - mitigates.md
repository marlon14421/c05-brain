---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1003.002"
stix_relationship_id: "relationship--789a2c4e-9152-4b83-a275-58f6b5262a81"
---
# Relationship 1230: M1026 — mitigates → T1003.002

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Do not put user or admin domain accounts in the local administrator groups across systems unless they are tightly controlled, as this is often equivalent to having a local administrator account with the same password on all systems. Follow best practices for design and administration of an enterprise network to limit privileged account use across administrative tiers.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--789a2c4e-9152-4b83-a275-58f6b5262a81`.
