---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1041"
target_object: "T1602.002"
stix_relationship_id: "relationship--38762462-11f6-4f44-bda3-4da3c2c8d70d"
---
# Relationship 0964: M1041 — mitigates → T1602.002

**Source object:** [[01 ATT&CK/M1041 - Encrypt Sensitive Information|M1041: Encrypt Sensitive Information]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1602.002 - Network Device Configuration Dump|T1602.002: Network Device Configuration Dump]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Configure SNMPv3 to use the highest level of security (authPriv) available.(Citation: US-CERT TA17-156A SNMP Abuse 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38762462-11f6-4f44-bda3-4da3c2c8d70d`.
