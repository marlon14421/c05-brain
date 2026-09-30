---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1557.004"
stix_relationship_id: "relationship--70f6424e-7bc0-4baf-9ed5-46f6e9b72427"
---
# Relationship 0350: M1031 — mitigates → T1557.004

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557.004 - Evil Twin|T1557.004: Evil Twin]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Wireless intrusion prevention systems (WIPS) can identify traffic patterns indicative of adversary-in-the-middle activity and scan for evils twins and rogue access points.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70f6424e-7bc0-4baf-9ed5-46f6e9b72427`.
