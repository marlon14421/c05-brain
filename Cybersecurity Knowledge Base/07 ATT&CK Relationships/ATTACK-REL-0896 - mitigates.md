---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1078.002"
stix_relationship_id: "relationship--0561610c-dbcd-454f-aa33-8a68086c0b3a"
---
# Relationship 0896: M1018 — mitigates → T1078.002

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Regularly review and manage domain accounts to ensure that only active, necessary accounts exist. Remove or disable inactive and unnecessary accounts to reduce the risk of adversaries abusing these accounts to gain unauthorized access or move laterally within the network.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0561610c-dbcd-454f-aa33-8a68086c0b3a`.
