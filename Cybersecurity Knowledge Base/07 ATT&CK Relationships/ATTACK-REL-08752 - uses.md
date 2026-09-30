---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0659"
target_object: "T1485"
stix_relationship_id: "relationship--063b76d3-a002-44a1-aafa-d626008ee786"
---
# Relationship 8752: S0659 — uses → T1485

**Source object:** [[01 ATT&CK/S0659 - Diavol|S0659: Diavol]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Diavol](https://attack.mitre.org/software/S0659) can delete specified files from a targeted system.(Citation: Fortinet Diavol July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--063b76d3-a002-44a1-aafa-d626008ee786`.
