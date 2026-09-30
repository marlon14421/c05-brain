---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1217"
target_object: "T1059.006"
stix_relationship_id: "relationship--1f8eebb8-84ef-4578-a020-50aa7286e7c6"
---
# Relationship 5371: S1217 — uses → T1059.006

**Source object:** [[01 ATT&CK/S1217 - VIRTUALPITA|S1217: VIRTUALPITA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPITA](https://attack.mitre.org/software/S1217) can call a Python script to run commands on a targeted guest virtual machine.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f8eebb8-84ef-4578-a020-50aa7286e7c6`.
