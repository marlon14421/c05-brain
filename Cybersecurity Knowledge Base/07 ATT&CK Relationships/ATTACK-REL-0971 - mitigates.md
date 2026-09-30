---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1553.003"
stix_relationship_id: "relationship--08dd36a7-dee0-4f25-b3dc-d030c32151f5"
---
# Relationship 0971: M1038 — mitigates → T1553.003

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1553.003 - SIP and Trust Provider Hijacking|T1553.003: SIP and Trust Provider Hijacking]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enable application control solutions such as AppLocker and/or Device Guard to block the loading of malicious SIP DLLs.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08dd36a7-dee0-4f25-b3dc-d030c32151f5`.
