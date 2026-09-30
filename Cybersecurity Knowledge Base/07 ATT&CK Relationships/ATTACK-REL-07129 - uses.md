---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1170"
target_object: "T1059.003"
stix_relationship_id: "relationship--34e80e15-32d2-4efb-91ed-2d91b08a4bee"
---
# Relationship 7129: S1170 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1170 - ODAgent|S1170: ODAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ODAgent](https://attack.mitre.org/software/S1170) can execute a specified command line passed via API.(Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34e80e15-32d2-4efb-91ed-2d91b08a4bee`.
