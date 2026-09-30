---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1030"
target_object: "T1098"
stix_relationship_id: "relationship--21ea4371-e692-4731-9f8c-c3f4dff3c775"
---
# Relationship 0712: M1030 — mitigates → T1098

**Source object:** [[01 ATT&CK/M1030 - Network Segmentation|M1030: Network Segmentation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Configure access controls and firewalls to limit access to critical systems and domain controllers. Most cloud environments support separate virtual private cloud (VPC) instances that enable further segmentation of cloud systems.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21ea4371-e692-4731-9f8c-c3f4dff3c775`.
