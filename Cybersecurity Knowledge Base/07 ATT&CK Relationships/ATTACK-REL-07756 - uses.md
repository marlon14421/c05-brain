---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1070.004"
stix_relationship_id: "relationship--2b772eaa-086e-4e04-a346-8cfac766f8f0"
---
# Relationship 7756: S1200 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can self-delete its executable file from the compromised system.(Citation: Cybereason StealBit Exfiltration Tool)(Citation: FBI Lockbit 2.0 FEB 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b772eaa-086e-4e04-a346-8cfac766f8f0`.
