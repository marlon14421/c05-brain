---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1505"
stix_relationship_id: "relationship--edbfcc84-4096-4839-b5eb-5025b70ccaca"
---
# Relationship 0276: M1018 — mitigates → T1505

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1505 - Server Software Component|T1505: Server Software Component]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enforce the principle of least privilege by limiting privileges of user accounts so only authorized accounts can modify and/or add server software components.(Citation: NSA and ASD Detect and Prevent Web Shells 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edbfcc84-4096-4839-b5eb-5025b70ccaca`.
