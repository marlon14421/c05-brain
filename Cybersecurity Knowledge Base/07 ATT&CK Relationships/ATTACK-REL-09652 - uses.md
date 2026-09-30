---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0452"
target_object: "T1057"
stix_relationship_id: "relationship--bfad86a1-f8bb-45eb-b7b9-5919ca4ef886"
---
# Relationship 9652: S0452 — uses → T1057

**Source object:** [[01 ATT&CK/S0452 - USBferry|S0452: USBferry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[USBferry](https://attack.mitre.org/software/S0452) can use tasklist to gather information about the process running on the infected system.(Citation: TrendMicro Tropic Trooper May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfad86a1-f8bb-45eb-b7b9-5919ca4ef886`.
