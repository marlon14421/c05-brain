---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1486"
stix_relationship_id: "relationship--8b245546-d5ed-4ff8-b5a6-7c97250ce026"
---
# Relationship 5590: S0576 — uses → T1486

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MegaCortex](https://attack.mitre.org/software/S0576) has used the open-source library, Mbed Crypto, and generated AES keys to carry out the file encryption process.(Citation: IBM MegaCortex)(Citation: mbed-crypto)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b245546-d5ed-4ff8-b5a6-7c97250ce026`.
