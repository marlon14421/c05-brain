---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1078.003"
stix_relationship_id: "relationship--8543032a-2f76-4837-90d3-ffd54f6e8708"
---
# Relationship 0797: M1018 — mitigates → T1078.003

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enforce user account management practices for local accounts to limit access and remove inactive or unused accounts. By doing so, you reduce the attack surface available to adversaries and prevent unauthorized access to local systems.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8543032a-2f76-4837-90d3-ffd54f6e8708`.
