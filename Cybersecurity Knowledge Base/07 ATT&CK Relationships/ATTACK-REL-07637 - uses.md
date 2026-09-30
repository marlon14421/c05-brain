---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1058"
target_object: "T1486"
stix_relationship_id: "relationship--2a28ee8a-0ecd-43da-a4f8-a653ef5fd123"
---
# Relationship 7637: S1058 — uses → T1486

**Source object:** [[01 ATT&CK/S1058 - Prestige|S1058: Prestige]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Prestige](https://attack.mitre.org/software/S1058) has leveraged the CryptoPP C++ library to encrypt files on target systems using AES and appended filenames with `.enc`.(Citation: Microsoft Prestige ransomware October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a28ee8a-0ecd-43da-a4f8-a653ef5fd123`.
