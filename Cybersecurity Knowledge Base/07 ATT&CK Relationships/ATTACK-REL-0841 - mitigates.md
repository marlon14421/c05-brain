---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1566.003"
stix_relationship_id: "relationship--311f8c01-21ac-48db-a036-581e9e49f07c"
---
# Relationship 0841: M1018 — mitigates → T1566.003

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1566.003 - Spearphishing via Service|T1566.003: Spearphishing via Service]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enforce strict user account management policies on third-party service accounts to control access and limit privileges. Configure accounts with the minimum permissions necessary to perform their roles and regularly review access levels. This minimizes the risk of adversaries exploiting service accounts to execute spearphishing attacks or gain unauthorized access to sensitive resources.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--311f8c01-21ac-48db-a036-581e9e49f07c`.
