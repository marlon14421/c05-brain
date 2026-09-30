---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1557.002"
stix_relationship_id: "relationship--8fe9affe-bf8d-4392-882d-d3e737eb5c43"
---
# Relationship 0482: M1042 — mitigates → T1557.002

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557.002 - ARP Cache Poisoning|T1557.002: ARP Cache Poisoning]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider disabling updating the ARP cache on gratuitous ARP replies.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8fe9affe-bf8d-4392-882d-d3e737eb5c43`.
