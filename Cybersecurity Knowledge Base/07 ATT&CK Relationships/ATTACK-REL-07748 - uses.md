---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1005"
stix_relationship_id: "relationship--035525fc-4549-4282-b85b-c7c07359124c"
---
# Relationship 7748: G0094 — uses → T1005

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has collected Office, PDF, and HWP documents from its victims.(Citation: Securelist Kimsuky Sept 2013)(Citation: Talos Kimsuky Nov 2021) [Kimsuky](https://attack.mitre.org/groups/G0094) has also harvested victim files through the use of the `RecentFiles()` function that collects paths of recently accessed files by parsing .lnk shortcuts from `%APPDATA%\Microsoft\Windows\Recent`.(Citation: Aryaka Kimsuky July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--035525fc-4549-4282-b85b-c7c07359124c`.
