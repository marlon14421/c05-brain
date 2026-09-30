---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0584"
target_object: "T1041"
stix_relationship_id: "relationship--1d17e8d5-7a65-4d67-bfec-0ef7cad974d9"
---
# Relationship 5444: S0584 — uses → T1041

**Source object:** [[01 ATT&CK/S0584 - AppleJeus|S0584: AppleJeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleJeus](https://attack.mitre.org/software/S0584) has exfiltrated collected host information to a C2 server.(Citation: CISA AppleJeus Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d17e8d5-7a65-4d67-bfec-0ef7cad974d9`.
