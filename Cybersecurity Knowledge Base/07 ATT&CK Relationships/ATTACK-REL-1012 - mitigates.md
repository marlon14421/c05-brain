---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1036"
target_object: "T1078.004"
stix_relationship_id: "relationship--b93fd13f-b11b-4f4b-9d77-977e7af41d5c"
---
# Relationship 1012: M1036 — mitigates → T1078.004

**Source object:** [[01 ATT&CK/M1036 - Account Use Policies|M1036: Account Use Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use conditional access policies to block logins from non-compliant devices or from outside defined organization IP ranges.(Citation: Microsoft Common Conditional Access Policies)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b93fd13f-b11b-4f4b-9d77-977e7af41d5c`.
