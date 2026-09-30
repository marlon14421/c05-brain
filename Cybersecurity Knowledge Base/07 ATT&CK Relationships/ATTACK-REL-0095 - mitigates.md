---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1020"
target_object: "T1090"
stix_relationship_id: "relationship--f229e2fb-3105-4ae5-abe1-d100209f702c"
---
# Relationship 0095: M1020 — mitigates → T1090

**Source object:** [[01 ATT&CK/M1020 - SSL-TLS Inspection|M1020: SSL/TLS Inspection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

If it is possible to inspect HTTPS traffic, the captures can be analyzed for connections that appear to be domain fronting.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f229e2fb-3105-4ae5-abe1-d100209f702c`.
