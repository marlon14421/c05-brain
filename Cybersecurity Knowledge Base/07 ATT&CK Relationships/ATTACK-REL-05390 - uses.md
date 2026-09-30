---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0612"
target_object: "T1548.002"
stix_relationship_id: "relationship--7fff37e5-a123-4d85-850e-7745d1e18650"
---
# Relationship 5390: S0612 — uses → T1548.002

**Source object:** [[01 ATT&CK/S0612 - WastedLocker|S0612: WastedLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548.002 - Bypass User Account Control|T1548.002: Bypass User Account Control]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WastedLocker](https://attack.mitre.org/software/S0612) can perform a UAC bypass if it is not executed with administrator rights or if the infected host runs Windows Vista or later.(Citation: NCC Group WastedLocker June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fff37e5-a123-4d85-850e-7745d1e18650`.
