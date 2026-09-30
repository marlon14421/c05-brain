---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1033"
target_object: "T1486"
stix_relationship_id: "relationship--696c0ce2-7829-4d95-baab-ae64db59c62a"
---
# Relationship 7935: S1033 — uses → T1486

**Source object:** [[01 ATT&CK/S1033 - DCSrv|S1033: DCSrv]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DCSrv](https://attack.mitre.org/software/S1033) has encrypted drives using the core encryption mechanism from DiskCryptor.(Citation: Checkpoint MosesStaff Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--696c0ce2-7829-4d95-baab-ae64db59c62a`.
