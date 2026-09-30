---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1556.006"
stix_relationship_id: "relationship--90d0d818-4a80-459c-9d57-ca9221eae57b"
---
# Relationship 0311: M1047 — mitigates → T1556.006

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.006 - Multi-Factor Authentication|T1556.006: Multi-Factor Authentication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Review MFA actions alongside authentication logs to ensure that MFA-based logins are functioning as intended. Review user accounts to ensure that all accounts have MFA enabled.(Citation: Mandiant Cloudy Logs 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90d0d818-4a80-459c-9d57-ca9221eae57b`.
