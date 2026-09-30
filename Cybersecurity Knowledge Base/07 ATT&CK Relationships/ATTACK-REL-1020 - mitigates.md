---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1055"
target_object: "T1480.002"
stix_relationship_id: "relationship--5ea008a7-d193-4ec6-b60b-68b4fec16690"
---
# Relationship 1020: M1055 — mitigates → T1480.002

**Source object:** [[01 ATT&CK/M1055 - Do Not Mitigate|M1055: Do Not Mitigate]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

[Execution Guardrails](https://attack.mitre.org/techniques/T1480) likely should not be mitigated with preventative controls because it may protect unintended targets from being compromised. If targeted, efforts should be focused on preventing adversary tools from running earlier in the chain of activity and on identifying subsequent malicious behavior if compromised.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ea008a7-d193-4ec6-b60b-68b4fec16690`.
