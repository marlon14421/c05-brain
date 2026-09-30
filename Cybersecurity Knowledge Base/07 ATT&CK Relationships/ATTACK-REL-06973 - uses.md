---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1055.004"
stix_relationship_id: "relationship--f5e7233b-6419-4c09-b95b-c43f3004f246"
---
# Relationship 6973: S0438 — uses → T1055.004

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.004 - Asynchronous Procedure Call|T1055.004: Asynchronous Procedure Call]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Attor](https://attack.mitre.org/software/S0438) performs the injection by attaching its code into the APC queue using NtQueueApcThread API.(Citation: ESET Attor Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5e7233b-6419-4c09-b95b-c43f3004f246`.
