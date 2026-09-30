---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0560"
target_object: "T1012"
stix_relationship_id: "relationship--184739bd-f45e-4f2b-8caf-19e2cb30ae92"
---
# Relationship 6327: S0560 — uses → T1012

**Source object:** [[01 ATT&CK/S0560 - TEARDROP|S0560: TEARDROP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TEARDROP](https://attack.mitre.org/software/S0560) checked that HKU\SOFTWARE\Microsoft\CTF existed before decoding its embedded payload.(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--184739bd-f45e-4f2b-8caf-19e2cb30ae92`.
