---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0168"
target_object: "T1055"
stix_relationship_id: "relationship--8acca861-11fd-49bd-8dbc-0b326f5303d6"
---
# Relationship 7356: S0168 — uses → T1055

**Source object:** [[01 ATT&CK/S0168 - Gazer|S0168: Gazer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gazer](https://attack.mitre.org/software/S0168) injects its communication module into an Internet accessible process through which it performs C2.(Citation: ESET Gazer Aug 2017)(Citation: Securelist WhiteBear Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8acca861-11fd-49bd-8dbc-0b326f5303d6`.
