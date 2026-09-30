---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0053"
target_object: "T1090.003"
stix_relationship_id: "relationship--6b3adc08-6687-4b92-a0bd-b12f6eecbf2b"
---
# Relationship 6650: C0053 — uses → T1090.003

**Source object:** [[01 ATT&CK/C0053 - FLORAHOX Activity|C0053: FLORAHOX Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) has routed traffic through a customized [Tor](https://attack.mitre.org/software/S0183) relay network layer.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b3adc08-6687-4b92-a0bd-b12f6eecbf2b`.
