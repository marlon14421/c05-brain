---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0170"
target_object: "T1059.005"
stix_relationship_id: "relationship--610fcccc-c03a-4bd1-8f86-95802fe33cba"
---
# Relationship 8768: S0170 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0170 - Helminth|S0170: Helminth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

One version of [Helminth](https://attack.mitre.org/software/S0170) consists of VBScript scripts.(Citation: Palo Alto OilRig May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--610fcccc-c03a-4bd1-8f86-95802fe33cba`.
