---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1012"
target_object: "T1140"
stix_relationship_id: "relationship--dfcd4d41-11f4-4891-9e49-7a725ab18d1d"
---
# Relationship 9181: S1012 — uses → T1140

**Source object:** [[01 ATT&CK/S1012 - PowerLess|S1012: PowerLess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerLess](https://attack.mitre.org/software/S1012) can use base64 and AES ECB decryption prior to execution of downloaded modules.(Citation: Cybereason PowerLess February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfcd4d41-11f4-4891-9e49-7a725ab18d1d`.
