---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0612"
target_object: "T1564.004"
stix_relationship_id: "relationship--c3e7ca65-d0b0-43bd-ae13-047c361f3a79"
---
# Relationship 7776: S0612 — uses → T1564.004

**Source object:** [[01 ATT&CK/S0612 - WastedLocker|S0612: WastedLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.004 - NTFS File Attributes|T1564.004: NTFS File Attributes]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WastedLocker](https://attack.mitre.org/software/S0612) has the ability to save and execute files as an alternate data stream (ADS).(Citation: Sentinel Labs WastedLocker July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3e7ca65-d0b0-43bd-ae13-047c361f3a79`.
