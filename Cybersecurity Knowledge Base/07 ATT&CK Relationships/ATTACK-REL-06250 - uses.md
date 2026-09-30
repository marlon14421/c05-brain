---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0639"
target_object: "T1486"
stix_relationship_id: "relationship--d4221b38-c9cf-4773-9a49-afa7b07b917a"
---
# Relationship 6250: S0639 — uses → T1486

**Source object:** [[01 ATT&CK/S0639 - Seth-Locker|S0639: Seth-Locker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Seth-Locker](https://attack.mitre.org/software/S0639) can encrypt files on a targeted system, appending them with the suffix .seth.(Citation: Trend Micro Ransomware February 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4221b38-c9cf-4773-9a49-afa7b07b917a`.
