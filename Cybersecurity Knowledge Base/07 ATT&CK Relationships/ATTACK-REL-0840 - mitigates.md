---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1547.006"
stix_relationship_id: "relationship--4907e8fb-e224-49a6-aa94-5a76afa714ba"
---
# Relationship 0840: M1026 — mitigates → T1547.006

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.006 - Kernel Modules and Extensions|T1547.006: Kernel Modules and Extensions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit access to the root account and prevent users from loading kernel modules and extensions through proper privilege separation and limiting Privilege Escalation opportunities.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4907e8fb-e224-49a6-aa94-5a76afa714ba`.
