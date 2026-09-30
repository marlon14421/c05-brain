---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1056"
target_object: "T1583.001"
stix_relationship_id: "relationship--c296b445-a4b5-4e73-91b0-0c6c9f3eed1b"
---
# Relationship 0950: M1056 — mitigates → T1583.001

**Source object:** [[01 ATT&CK/M1056 - Pre-compromise|M1056: Pre-compromise]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Organizations may intentionally register similar domains to their own to deter adversaries from creating typosquatting domains. Other facets of this technique cannot be easily mitigated with preventive controls since it is based on behaviors performed outside of the scope of enterprise defenses and controls.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c296b445-a4b5-4e73-91b0-0c6c9f3eed1b`.
