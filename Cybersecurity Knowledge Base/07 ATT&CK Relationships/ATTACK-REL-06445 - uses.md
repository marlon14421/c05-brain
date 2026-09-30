---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0659"
target_object: "T1057"
stix_relationship_id: "relationship--31667cdd-1ac5-46f5-8dbd-9ebaf09f00a9"
---
# Relationship 6445: S0659 — uses → T1057

**Source object:** [[01 ATT&CK/S0659 - Diavol|S0659: Diavol]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Diavol](https://attack.mitre.org/software/S0659) has used `CreateToolhelp32Snapshot`, `Process32First`, and `Process32Next` API calls to enumerate the running processes in the system.(Citation: Fortinet Diavol July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31667cdd-1ac5-46f5-8dbd-9ebaf09f00a9`.
