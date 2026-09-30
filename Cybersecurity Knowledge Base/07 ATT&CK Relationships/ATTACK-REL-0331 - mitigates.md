---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1505.004"
stix_relationship_id: "relationship--05ae3ecc-6920-4828-b708-f0acdf0e2ff3"
---
# Relationship 0331: M1026 — mitigates → T1505.004

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1505.004 - IIS Components|T1505.004: IIS Components]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Do not allow administrator accounts that have permissions to add IIS components to be used for day-to-day operations that may expose these permissions to potential adversaries and/or other unprivileged systems.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05ae3ecc-6920-4828-b708-f0acdf0e2ff3`.
