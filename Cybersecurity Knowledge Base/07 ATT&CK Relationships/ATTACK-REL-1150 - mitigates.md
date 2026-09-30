---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1035"
target_object: "T1542"
stix_relationship_id: "relationship--00e2899a-beb7-448a-b003-a8b67e0b0daf"
---
# Relationship 1150: M1035 — mitigates → T1542

**Source object:** [[01 ATT&CK/M1035 - Limit Access to Resource Over Network|M1035: Limit Access to Resource Over Network]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1542 - Pre-OS Boot|T1542: Pre-OS Boot]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent access to file shares, remote access to systems, unnecessary services. Mechanisms to limit access may include use of network concentrators, RDP gateways, etc.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00e2899a-beb7-448a-b003-a8b67e0b0daf`.
