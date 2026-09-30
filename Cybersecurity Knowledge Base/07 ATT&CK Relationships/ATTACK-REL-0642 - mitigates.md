---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1602.002"
stix_relationship_id: "relationship--9160a38d-799b-431d-a5d1-a9b4099ab8b1"
---
# Relationship 0642: M1031 — mitigates → T1602.002

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1602.002 - Network Device Configuration Dump|T1602.002: Network Device Configuration Dump]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Configure intrusion prevention devices to detect SNMP queries and commands from unauthorized sources. Create signatures to detect Smart Install (SMI) usage from sources other than trusted director.(Citation: US-CERT TA18-106A Network Infrastructure Devices 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9160a38d-799b-431d-a5d1-a9b4099ab8b1`.
