---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0465"
target_object: "T1204.002"
stix_relationship_id: "relationship--7c9b61d8-30ff-4594-9cfb-90f2db44ca0e"
---
# Relationship 9333: S0465 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0465 - CARROTBALL|S0465: CARROTBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CARROTBALL](https://attack.mitre.org/software/S0465) has been executed through users being lured into opening malicious e-mail attachments.(Citation: Unit 42 CARROTBAT January 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c9b61d8-30ff-4594-9cfb-90f2db44ca0e`.
