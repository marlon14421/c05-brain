---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1137"
target_object: "T1486"
stix_relationship_id: "relationship--187b15ea-f564-4abf-80d8-756115f47be2"
---
# Relationship 7033: S1137 — uses → T1486

**Source object:** [[01 ATT&CK/S1137 - Moneybird|S1137: Moneybird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moneybird](https://attack.mitre.org/software/S1137) targets a common set of file types such as documents, certificates, and database files for encryption while avoiding executable, dynamic linked libraries, and similar items.(Citation: CheckPoint Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--187b15ea-f564-4abf-80d8-756115f47be2`.
