---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1212"
target_object: "T1486"
stix_relationship_id: "relationship--a3e75daa-c9a5-41c5-9225-dd7b69400edc"
---
# Relationship 5035: S1212 — uses → T1486

**Source object:** [[01 ATT&CK/S1212 - RansomHub|S1212: RansomHub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) can use Elliptic Curve Encryption to encrypt files on targeted systems.(Citation: CISA RansomHub AUG 2024) [RansomHub](https://attack.mitre.org/software/S1212) can also skip content at regular intervals (ex. encrypt 1 MB, skip 3 MB) to optomize performance and enable faster encryption for large files.(Citation: Group-IB RansomHub FEB 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3e75daa-c9a5-41c5-9225-dd7b69400edc`.
