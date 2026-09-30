---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1056"
target_object: "T1589.002"
stix_relationship_id: "relationship--611ad683-7772-4592-bbd4-e5589591a76e"
---
# Relationship 0831: M1056 — mitigates → T1589.002

**Source object:** [[01 ATT&CK/M1056 - Pre-compromise|M1056: Pre-compromise]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1589.002 - Email Addresses|T1589.002: Email Addresses]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

This technique cannot be easily mitigated with preventive controls since it is based on behaviors performed outside of the scope of enterprise defenses and controls. Efforts should focus on minimizing the amount and sensitivity of data available to external parties.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--611ad683-7772-4592-bbd4-e5589591a76e`.
