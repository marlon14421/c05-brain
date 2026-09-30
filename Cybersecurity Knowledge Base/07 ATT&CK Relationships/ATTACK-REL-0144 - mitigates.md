---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1547.004"
stix_relationship_id: "relationship--bfce35b9-7ae9-4194-83a7-5e5ff1481551"
---
# Relationship 0144: M1018 — mitigates → T1547.004

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.004 - Winlogon Helper DLL|T1547.004: Winlogon Helper DLL]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the privileges of user accounts so that only authorized administrators can perform Winlogon helper changes.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfce35b9-7ae9-4194-83a7-5e5ff1481551`.
