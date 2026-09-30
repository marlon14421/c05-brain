---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1178"
target_object: "T1486"
stix_relationship_id: "relationship--78a8b5dd-0dfc-4dea-bc07-b5a3a10f0483"
---
# Relationship 6198: S1178 — uses → T1486

**Source object:** [[01 ATT&CK/S1178 - ShrinkLocker|S1178: ShrinkLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShrinkLocker](https://attack.mitre.org/software/S1178) uses the legitimate BitLocker application to encrypt victim files for ransom.(Citation: Kaspersky ShrinkLocker 2024)(Citation: Splunk ShrinkLocker 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78a8b5dd-0dfc-4dea-bc07-b5a3a10f0483`.
