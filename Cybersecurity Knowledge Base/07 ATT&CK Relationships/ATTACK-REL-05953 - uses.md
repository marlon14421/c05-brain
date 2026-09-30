---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0476"
target_object: "T1071.001"
stix_relationship_id: "relationship--4143e83e-40a1-4d10-babf-9affba3cb101"
---
# Relationship 5953: S0476 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0476 - Valak|S0476: Valak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Valak](https://attack.mitre.org/software/S0476) has used HTTP in communications with C2.(Citation: Cybereason Valak May 2020)(Citation: Unit 42 Valak July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4143e83e-40a1-4d10-babf-9affba3cb101`.
