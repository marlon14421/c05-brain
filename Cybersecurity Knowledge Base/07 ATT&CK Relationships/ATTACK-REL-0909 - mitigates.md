---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1053.002"
stix_relationship_id: "relationship--be34e043-48a0-4192-a877-e8520a2800cc"
---
# Relationship 0909: M1018 — mitigates → T1053.002

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1053.002 - At|T1053.002: At]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit privileges of user accounts and remediate Privilege Escalation vectors so only authorized administrators can create scheduled tasks on remote systems. In Linux environments, users account-level access to [at](https://attack.mitre.org/software/S0110) can be managed using at.allow and at.deny files. Users listed in the at.allow are enabled to schedule actions using at, whereas users listed in at.deny file disabled from the utility.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be34e043-48a0-4192-a877-e8520a2800cc`.
