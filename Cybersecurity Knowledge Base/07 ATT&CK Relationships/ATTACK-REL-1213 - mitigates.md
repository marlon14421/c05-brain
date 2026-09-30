---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1027"
target_object: "T1078.002"
stix_relationship_id: "relationship--bd2a538d-7e43-49bd-86fc-f4eae98e8d84"
---
# Relationship 1213: M1027 — mitigates → T1078.002

**Source object:** [[01 ATT&CK/M1027 - Password Policies|M1027: Password Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Implement and enforce strong password policies for domain accounts to ensure passwords are complex, unique, and regularly rotated. This reduces the likelihood of password guessing, credential stuffing, and other attack methods that rely on weak or static credentials.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd2a538d-7e43-49bd-86fc-f4eae98e8d84`.
