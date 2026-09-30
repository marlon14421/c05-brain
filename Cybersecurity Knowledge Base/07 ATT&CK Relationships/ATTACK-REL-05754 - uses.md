---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1486"
stix_relationship_id: "relationship--18fbf9cb-5008-4701-99de-11cfa35978df"
---
# Relationship 5754: S9020 — uses → T1486

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) can incorporate a ransom command to encrypt specified files and folders.(Citation: Kaspersky LODEINFO Part II OCT 2022)(Citation: ESET MirrorFace DEC 2022)(Citation: ITOCHU LODEINFO JAN 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18fbf9cb-5008-4701-99de-11cfa35978df`.
