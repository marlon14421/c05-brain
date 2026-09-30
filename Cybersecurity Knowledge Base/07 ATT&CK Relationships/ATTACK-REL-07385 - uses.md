---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0335"
target_object: "T1102"
stix_relationship_id: "relationship--1ef0015d-f4ab-49fe-a5b2-89e601ea5cfa"
---
# Relationship 7385: S0335 — uses → T1102

**Source object:** [[01 ATT&CK/S0335 - Carbon|S0335: Carbon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbon](https://attack.mitre.org/software/S0335) can use Pastebin to receive C2 commands.(Citation: Accenture HyperStack October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ef0015d-f4ab-49fe-a5b2-89e601ea5cfa`.
