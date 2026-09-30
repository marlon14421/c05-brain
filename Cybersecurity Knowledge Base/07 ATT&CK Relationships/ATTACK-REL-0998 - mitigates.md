---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1020"
target_object: "T1573.002"
stix_relationship_id: "relationship--bfb8c372-82f0-4bdb-8083-5fae8b8ef185"
---
# Relationship 0998: M1020 — mitigates → T1573.002

**Source object:** [[01 ATT&CK/M1020 - SSL-TLS Inspection|M1020: SSL/TLS Inspection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

SSL/TLS inspection can be used to see the contents of encrypted sessions to look for network-based indicators of malware communication protocols.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfb8c372-82f0-4bdb-8083-5fae8b8ef185`.
