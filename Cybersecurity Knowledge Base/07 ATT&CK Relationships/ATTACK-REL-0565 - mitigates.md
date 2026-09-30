---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1602"
stix_relationship_id: "relationship--c217ea78-f411-4dd1-a019-8aa3e366df23"
---
# Relationship 0565: M1031 — mitigates → T1602

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1602 - Data from Configuration Repository|T1602: Data from Configuration Repository]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Configure intrusion prevention devices to detect SNMP queries and commands from unauthorized sources.(Citation: US-CERT-TA18-106A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c217ea78-f411-4dd1-a019-8aa3e366df23`.
