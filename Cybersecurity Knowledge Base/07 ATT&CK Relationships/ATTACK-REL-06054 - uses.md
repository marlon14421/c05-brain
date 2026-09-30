---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0005"
target_object: "T1204.002"
stix_relationship_id: "relationship--48cff69b-577c-4837-b894-95b19f255134"
---
# Relationship 6054: C0005 — uses → T1204.002

**Source object:** [[01 ATT&CK/C0005 - Operation Spalax|C0005: Operation Spalax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Spalax](https://attack.mitre.org/campaigns/C0005), the threat actors relied on a victim to open a PDF document and click on an embedded malicious link to download malware.(Citation: ESET Operation Spalax Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48cff69b-577c-4837-b894-95b19f255134`.
