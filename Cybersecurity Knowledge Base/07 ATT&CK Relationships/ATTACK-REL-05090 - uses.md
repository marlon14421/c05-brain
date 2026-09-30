---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0546"
target_object: "T1102"
stix_relationship_id: "relationship--3a200957-9a8b-407e-a23f-cea1ef8236e6"
---
# Relationship 5090: S0546 — uses → T1102

**Source object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpStage](https://attack.mitre.org/software/S0546) has used a legitimate web service for evading detection.(Citation: Cybereason Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a200957-9a8b-407e-a23f-cea1ef8236e6`.
