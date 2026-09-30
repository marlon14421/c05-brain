---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1024"
target_object: "T1505.005"
stix_relationship_id: "relationship--3a3dd5f2-61af-4617-81b0-c12900f5f8e6"
---
# Relationship 0368: M1024 — mitigates → T1505.005

**Source object:** [[01 ATT&CK/M1024 - Restrict Registry Permissions|M1024: Restrict Registry Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1505.005 - Terminal Services DLL|T1505.005: Terminal Services DLL]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider using Group Policy to configure and block modifications to Terminal Services parameters in the Registry.(Citation: Microsoft System Services Fundamentals)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a3dd5f2-61af-4617-81b0-c12900f5f8e6`.
