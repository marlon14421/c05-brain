---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0020"
target_object: "T1070.006"
stix_relationship_id: "relationship--a6350331-0c0d-4d0d-90a3-d5cc3e420875"
---
# Relationship 6436: S0020 — uses → T1070.006

**Source object:** [[01 ATT&CK/S0020 - China Chopper|S0020: China Chopper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[China Chopper](https://attack.mitre.org/software/S0020)'s server component can change the timestamp of files.(Citation: FireEye Periscope March 2018)(Citation: Lee 2013)(Citation: NCSC Joint Report Public Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6350331-0c0d-4d0d-90a3-d5cc3e420875`.
