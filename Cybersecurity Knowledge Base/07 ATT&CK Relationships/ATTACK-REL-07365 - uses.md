---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0476"
target_object: "T1041"
stix_relationship_id: "relationship--8ae91ec7-32ed-46a2-9bc2-1c7b856c3cc7"
---
# Relationship 7365: S0476 — uses → T1041

**Source object:** [[01 ATT&CK/S0476 - Valak|S0476: Valak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Valak](https://attack.mitre.org/software/S0476) has the ability to exfiltrate data over the C2 channel.(Citation: Cybereason Valak May 2020)(Citation: Unit 42 Valak July 2020)(Citation: SentinelOne Valak June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ae91ec7-32ed-46a2-9bc2-1c7b856c3cc7`.
