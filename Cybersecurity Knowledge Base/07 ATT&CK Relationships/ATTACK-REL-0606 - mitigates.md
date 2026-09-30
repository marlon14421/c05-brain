---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1003.004"
stix_relationship_id: "relationship--bce3518d-52d4-4dc3-9de0-4d801048220d"
---
# Relationship 0606: M1026 — mitigates → T1003.004

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.004 - LSA Secrets|T1003.004: LSA Secrets]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Follow best practices for design and administration of an enterprise network to limit privileged account use across administrative tiers.(Citation: Tilbury Windows Credentials)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bce3518d-52d4-4dc3-9de0-4d801048220d`.
