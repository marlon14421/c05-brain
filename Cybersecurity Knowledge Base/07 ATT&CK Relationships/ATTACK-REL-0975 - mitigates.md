---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1095"
stix_relationship_id: "relationship--418bde38-35eb-44bc-a454-ad7d2918bda5"
---
# Relationship 0975: M1031 — mitigates → T1095

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Network intrusion detection and prevention systems that use network signatures to identify traffic for specific adversary malware can be used to mitigate activity at the network level.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--418bde38-35eb-44bc-a454-ad7d2918bda5`.
