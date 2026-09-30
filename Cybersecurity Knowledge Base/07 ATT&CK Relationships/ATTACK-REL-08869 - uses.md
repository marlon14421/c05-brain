---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0038"
target_object: "T1486"
stix_relationship_id: "relationship--0fbd1a64-07c1-4b5f-bb3a-2de93a9088a9"
---
# Relationship 8869: C0038 — uses → T1486

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [HomeLand Justice](https://attack.mitre.org/campaigns/C0038), threat actors used [ROADSWEEP](https://attack.mitre.org/software/S1150) ransomware to encrypt files on targeted systems.(Citation: Mandiant ROADSWEEP August 2022)(Citation: CISA Iran Albanian Attacks September 2022)(Citation: Microsoft Albanian Government Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0fbd1a64-07c1-4b5f-bb3a-2de93a9088a9`.
