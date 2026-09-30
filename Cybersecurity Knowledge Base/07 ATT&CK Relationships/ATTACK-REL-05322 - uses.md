---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0561"
target_object: "T1102"
stix_relationship_id: "relationship--cebec7e0-7be7-4bcf-936f-bd7622d559c7"
---
# Relationship 5322: S0561 — uses → T1102

**Source object:** [[01 ATT&CK/S0561 - GuLoader|S0561: GuLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GuLoader](https://attack.mitre.org/software/S0561) has the ability to download malware from Google Drive.(Citation: Medium Eli Salem GuLoader April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cebec7e0-7be7-4bcf-936f-bd7622d559c7`.
