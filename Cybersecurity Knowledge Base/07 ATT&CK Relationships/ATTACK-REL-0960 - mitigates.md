---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1136.003"
stix_relationship_id: "relationship--6a11c7bd-61ef-4b08-bee5-856f3bd401d1"
---
# Relationship 0960: M1026 — mitigates → T1136.003

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1136.003 - Cloud Account|T1136.003: Cloud Account]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the number of accounts with permissions to create other accounts. Do not allow privileged accounts to be used for day-to-day operations that may expose them to potential adversaries on unprivileged systems.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a11c7bd-61ef-4b08-bee5-856f3bd401d1`.
