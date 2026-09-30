---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1078.004"
stix_relationship_id: "relationship--68ad793a-2678-4537-8480-8086fd4d757e"
---
# Relationship 1059: M1032 — mitigates → T1078.004

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use multi-factor authentication for cloud accounts, especially privileged accounts. This can be implemented in a variety of forms (e.g. hardware, virtual, SMS), and can also be audited using administrative reporting features.(Citation: AWS - IAM Console Best Practices)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68ad793a-2678-4537-8480-8086fd4d757e`.
