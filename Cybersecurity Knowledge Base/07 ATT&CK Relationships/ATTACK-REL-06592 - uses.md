---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0034"
target_object: "T1008"
stix_relationship_id: "relationship--a713d0d3-2897-4da2-995f-df3a40f04b29"
---
# Relationship 6592: S0034 — uses → T1008

**Source object:** [[01 ATT&CK/S0034 - NETEAGLE|S0034: NETEAGLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETEAGLE](https://attack.mitre.org/software/S0034) will attempt to detect if the infected host is configured to a proxy. If so, [NETEAGLE](https://attack.mitre.org/software/S0034) will send beacons via an HTTP POST request; otherwise it will send beacons via UDP/6000.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a713d0d3-2897-4da2-995f-df3a40f04b29`.
