---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1685.003"
stix_relationship_id: "relationship--fe03f972-e88a-4eca-bb43-5f7a8ac4a9ad"
---
# Relationship 1185: M1038 — mitigates → T1685.003

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1685.003 - Modify or Spoof Tool UI|T1685.003: Modify or Spoof Tool UI]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use application controls to mitigate installation and use of payloads that may be utilized to spoof security alerting.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe03f972-e88a-4eca-bb43-5f7a8ac4a9ad`.
