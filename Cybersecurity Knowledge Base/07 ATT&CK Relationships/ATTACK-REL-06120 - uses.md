---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1018"
stix_relationship_id: "relationship--de93ce86-0bf9-4959-ab2b-b55df654b9f8"
---
# Relationship 6120: S1242 — uses → T1018

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can enumerate domain-connected hosts during its discovery phase.(Citation: Picus Qilin MAR 2025)(Citation: Sophos Qilin MSP APR 2025)(Citation: Cisco Talos Qilin Ransomware OCT 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de93ce86-0bf9-4959-ab2b-b55df654b9f8`.
