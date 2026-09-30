---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1078.001"
stix_relationship_id: "relationship--3e2212a9-9347-46ac-ae96-04e558973779"
---
# Relationship 0895: M1032 — mitigates → T1078.001

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.001 - Default Accounts|T1078.001: Default Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Implement multi-factor authentication (MFA) for default accounts whenever possible to prevent unauthorized access, even if credentials for these accounts are compromised. MFA adds an additional layer of security that requires more than just a username and password, making it significantly harder for adversaries to exploit these accounts for initial access or lateral movement.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e2212a9-9347-46ac-ae96-04e558973779`.
