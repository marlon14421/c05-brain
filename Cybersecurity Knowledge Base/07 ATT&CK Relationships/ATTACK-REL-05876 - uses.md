---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1204.002"
stix_relationship_id: "relationship--38a6e4b2-40c2-41f2-a415-7fbf586cc232"
---
# Relationship 5876: S0198 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) has been executed through luring victims into opening malicious documents.(Citation: FireEye NETWIRE March 2019)(Citation: Unit 42 NETWIRE April 2020)(Citation: Proofpoint NETWIRE December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38a6e4b2-40c2-41f2-a415-7fbf586cc232`.
