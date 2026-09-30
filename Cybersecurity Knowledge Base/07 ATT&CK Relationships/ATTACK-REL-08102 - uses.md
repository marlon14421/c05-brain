---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1106"
stix_relationship_id: "relationship--3c132a1b-053d-450b-8a4f-cabf30317075"
---
# Relationship 8102: S0455 — uses → T1106

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has used native WINAPI calls.(Citation: Medium Metamorfo Apr 2020)(Citation: Fortinet Metamorfo Feb 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c132a1b-053d-450b-8a4f-cabf30317075`.
