---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0228"
target_object: "T1059.007"
stix_relationship_id: "relationship--2a94575a-8e47-4d69-964b-f96210a673bd"
---
# Relationship 5298: S0228 — uses → T1059.007

**Source object:** [[01 ATT&CK/S0228 - NanHaiShu|S0228: NanHaiShu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NanHaiShu](https://attack.mitre.org/software/S0228) executes additional Jscript code on the victim's machine.(Citation: fsecure NanHaiShu July 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a94575a-8e47-4d69-964b-f96210a673bd`.
