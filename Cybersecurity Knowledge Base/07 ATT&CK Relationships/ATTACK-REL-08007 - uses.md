---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1486"
stix_relationship_id: "relationship--c7daa7ca-ca5a-4940-a370-d9eccb8f3c9a"
---
# Relationship 8007: S0611 — uses → T1486

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clop](https://attack.mitre.org/software/S0611) can encrypt files using AES, RSA, and RC4 and will add the ".clop" extension to encrypted files.(Citation: Mcafee Clop Aug 2019)(Citation: Unit42 Clop April 2021)(Citation: Cybereason Clop Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7daa7ca-ca5a-4940-a370-d9eccb8f3c9a`.
