---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1101"
target_object: "T1005"
stix_relationship_id: "relationship--aa0819dc-ed46-4908-af81-cdcd5c4d1845"
---
# Relationship 6078: S1101 — uses → T1005

**Source object:** [[01 ATT&CK/S1101 - LoFiSe|S1101: LoFiSe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoFiSe](https://attack.mitre.org/software/S1101) can collect files of interest from targeted systems.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa0819dc-ed46-4908-af81-cdcd5c4d1845`.
