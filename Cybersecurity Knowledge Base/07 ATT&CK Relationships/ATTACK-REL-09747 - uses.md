---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0264"
target_object: "T1030"
stix_relationship_id: "relationship--1abf4f3f-85e7-4bd1-9432-bddd40a0ad75"
---
# Relationship 9747: S0264 — uses → T1030

**Source object:** [[01 ATT&CK/S0264 - OopsIE|S0264: OopsIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OopsIE](https://attack.mitre.org/software/S0264) exfiltrates command output and collected files to its C2 server in 1500-byte blocks.(Citation: Unit 42 OopsIE! Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1abf4f3f-85e7-4bd1-9432-bddd40a0ad75`.
