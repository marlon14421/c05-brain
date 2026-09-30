---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0113"
target_object: "T1082"
stix_relationship_id: "relationship--7adaf2f3-52f2-40aa-b1ae-2fd2f05d9d56"
---
# Relationship 6380: S0113 — uses → T1082

**Source object:** [[01 ATT&CK/S0113 - Prikormka|S0113: Prikormka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A module in [Prikormka](https://attack.mitre.org/software/S0113) collects information from the victim about Windows OS version, computer name, battery info, and physical memory.(Citation: ESET Operation Groundbait)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7adaf2f3-52f2-40aa-b1ae-2fd2f05d9d56`.
