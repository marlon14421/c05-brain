---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1090.001"
stix_relationship_id: "relationship--406ca789-682f-4e08-bb7e-60421923ee09"
---
# Relationship 5075: S0154 — uses → T1090.001

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.001 - Internal Proxy|T1090.001: Internal Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can be configured to have commands relayed over a peer-to-peer network of infected hosts. This can be used to limit the number of egress points, or provide access to a host without direct internet access.(Citation: cobaltstrike manual)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--406ca789-682f-4e08-bb7e-60421923ee09`.
