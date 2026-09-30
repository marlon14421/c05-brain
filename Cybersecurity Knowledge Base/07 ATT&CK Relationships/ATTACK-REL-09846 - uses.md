---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1059.005"
stix_relationship_id: "relationship--f5726b93-09c6-4130-8e87-5916338b438e"
---
# Relationship 9846: S1122 — uses → T1059.005

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122)’s dropper uses VBS files to install payloads and perform execution.(Citation: SCILabs Malteiro 2021)(Citation: ESET Security Mispadu Facebook Ads 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5726b93-09c6-4130-8e87-5916338b438e`.
