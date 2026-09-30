---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1053"
target_object: "T1547.001"
stix_relationship_id: "relationship--4c362fcd-939d-48e8-9279-731a663875b0"
---
# Relationship 6215: S1053 — uses → T1547.001

**Source object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053) has been executed via the `RunOnce` Registry key to run itself on safe mode.(Citation: Trend Micro AvosLocker Apr 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c362fcd-939d-48e8-9279-731a663875b0`.
