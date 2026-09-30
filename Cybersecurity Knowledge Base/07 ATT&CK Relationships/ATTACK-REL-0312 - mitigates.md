---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1027"
target_object: "T1021"
stix_relationship_id: "relationship--ed9cb2bb-5c45-45f1-a0d5-4458609a5ab5"
---
# Relationship 0312: M1027 — mitigates → T1021

**Source object:** [[01 ATT&CK/M1027 - Password Policies|M1027: Password Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021 - Remote Services|T1021: Remote Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Do not reuse local administrator account passwords across systems. Ensure password complexity and uniqueness such that the passwords cannot be cracked or guessed.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed9cb2bb-5c45-45f1-a0d5-4458609a5ab5`.
