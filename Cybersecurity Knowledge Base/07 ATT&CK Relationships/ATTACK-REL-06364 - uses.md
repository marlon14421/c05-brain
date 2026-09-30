---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1083"
stix_relationship_id: "relationship--7e836d44-0047-4192-81fd-6fb8ff0cdbda"
---
# Relationship 6364: S0611 — uses → T1083

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clop](https://attack.mitre.org/software/S0611) has searched folders and subfolders for files to encrypt.(Citation: Mcafee Clop Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e836d44-0047-4192-81fd-6fb8ff0cdbda`.
