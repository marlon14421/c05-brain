---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1030"
target_object: "T1571"
stix_relationship_id: "relationship--840fc319-2583-4a2b-8363-1a7e3fa33157"
---
# Relationship 1120: M1030 — mitigates → T1571

**Source object:** [[01 ATT&CK/M1030 - Network Segmentation|M1030: Network Segmentation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Properly configure firewalls and proxies to limit outgoing traffic to only necessary ports for that particular network segment.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--840fc319-2583-4a2b-8363-1a7e3fa33157`.
