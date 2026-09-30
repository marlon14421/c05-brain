---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1179"
target_object: "T1518.001"
stix_relationship_id: "relationship--83082ae7-c6bd-4595-8fe5-3016e8879119"
---
# Relationship 7896: S1179 — uses → T1518.001

**Source object:** [[01 ATT&CK/S1179 - Exbyte|S1179: Exbyte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Exbyte](https://attack.mitre.org/software/S1179) checks for the presence of various security software products during execution.(Citation: Symantec BlackByte 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83082ae7-c6bd-4595-8fe5-3016e8879119`.
