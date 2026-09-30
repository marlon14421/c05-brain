---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1003.008"
stix_relationship_id: "relationship--4274e62f-1dc9-47d0-800a-f812cfe4e071"
---
# Relationship 0192: M1026 — mitigates → T1003.008

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.008 - -etc-passwd and -etc-shadow|T1003.008: /etc/passwd and /etc/shadow]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Follow best practices in restricting access to privileged accounts to avoid hostile programs from accessing such sensitive information.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4274e62f-1dc9-47d0-800a-f812cfe4e071`.
