---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1556"
stix_relationship_id: "relationship--d3851a98-39b3-4105-ba93-c0cd91eb01eb"
---
# Relationship 0139: M1018 — mitigates → T1556

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure that proper policies are implemented to dictate the the secure enrollment and deactivation of authentication mechanisms, such as MFA, for user accounts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3851a98-39b3-4105-ba93-c0cd91eb01eb`.
