---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0136"
target_object: "T1036.005"
stix_relationship_id: "relationship--a67d4b9b-0c8f-41d8-a7f2-6d4c61fcb1ea"
---
# Relationship 6152: S0136 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0136 - USBStealer|S0136: USBStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[USBStealer](https://attack.mitre.org/software/S0136) mimics a legitimate Russian program called USB Disk Security.(Citation: ESET Sednit USBStealer 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a67d4b9b-0c8f-41d8-a7f2-6d4c61fcb1ea`.
