---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1078"
stix_relationship_id: "relationship--eed29e0f-59c1-4fab-8268-3f0571e90748"
---
# Relationship 1168: M1015 — mitigates → T1078

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disable legacy authentication, which does not support MFA, and require the use of modern authentication protocols instead.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eed29e0f-59c1-4fab-8268-3f0571e90748`.
