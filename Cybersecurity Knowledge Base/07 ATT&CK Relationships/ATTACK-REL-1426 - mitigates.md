---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1030"
target_object: "T1602.002"
stix_relationship_id: "relationship--3dbcc83a-1e60-4ae4-a1f9-b37e1aa7d7b0"
---
# Relationship 1426: M1030 — mitigates → T1602.002

**Source object:** [[01 ATT&CK/M1030 - Network Segmentation|M1030: Network Segmentation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1602.002 - Network Device Configuration Dump|T1602.002: Network Device Configuration Dump]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Segregate SNMP traffic on a separate management network.(Citation: US-CERT TA17-156A SNMP Abuse 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dbcc83a-1e60-4ae4-a1f9-b37e1aa7d7b0`.
