---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1106"
stix_relationship_id: "relationship--83aab8bd-08b0-4f18-b78d-fe5f071902fe"
---
# Relationship 5529: S1200 — uses → T1106

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can use native APIs including `LoadLibraryExA` for execution and `NtSetInformationProcess` for defense evasion purposes.(Citation: Cybereason StealBit Exfiltration Tool)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83aab8bd-08b0-4f18-b78d-fe5f071902fe`.
