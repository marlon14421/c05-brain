---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9018"
target_object: "T1055.004"
stix_relationship_id: "relationship--06ba4a6e-c3aa-4c02-b21d-b1523759ec2b"
---
# Relationship 8456: S9018 — uses → T1055.004

**Source object:** [[01 ATT&CK/S9018 - HeartCrypt|S9018: HeartCrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.004 - Asynchronous Procedure Call|T1055.004: Asynchronous Procedure Call]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HeartCrypt](https://attack.mitre.org/software/S9018) has the ability to use `NtQueueApcThread` as an alternate method for process injection.(Citation: Palo Alto HeartCrypt DEC 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06ba4a6e-c3aa-4c02-b21d-b1523759ec2b`.
