---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0341"
target_object: "T1218.010"
stix_relationship_id: "relationship--ee9da7e8-12a5-4b77-84ce-a5453874a070"
---
# Relationship 9297: S0341 — uses → T1218.010

**Source object:** [[01 ATT&CK/S0341 - Xbash|S0341: Xbash]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Xbash](https://attack.mitre.org/software/S0341) can use regsvr32 for executing scripts.(Citation: Unit42 Xbash Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee9da7e8-12a5-4b77-84ce-a5453874a070`.
