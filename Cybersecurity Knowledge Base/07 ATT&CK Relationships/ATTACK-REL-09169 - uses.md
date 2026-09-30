---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1055.004"
stix_relationship_id: "relationship--a6fe230f-9e76-46a5-a235-2990009d8c4a"
---
# Relationship 9169: S0483 — uses → T1055.004

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.004 - Asynchronous Procedure Call|T1055.004: Asynchronous Procedure Call]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has used ZwQueueApcThread to inject itself into remote processes.(Citation: IBM IcedID November 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6fe230f-9e76-46a5-a235-2990009d8c4a`.
